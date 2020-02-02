# Task_1-Login-Page-Form-with-React-Native

Steps for creation of Login Page Form with React Native :

1.Create a react native project( Run Node.js in Command Prompt)
      //Install react-native
	  npm install -g react-native-cli
      npm install -g yarn.
	 // Create a Project
	 react-native init LoginForm.

2. Under the Project(Create 'src' folder for the source -> And under ‘src‘, create another folder for ‘pages‘ where we will put our js files. Create a Login.js and Signup.js files under ‘pages‘.)
3.Move to Form Activity. ( add AppRegistry, StyleSheet, Text, View, TextInput, TouchableOpacity, AsyncStorage and Keyboard component in import block.)
	import React, { Component } from 'react';
	import { StyleSheet, Text, View, TextInput, TouchableOpacity, AsyncStorage, Keyboard } from 'react-native';
4.Use Navigator for redirection to other screens. I use React-native Router Flux (To run node.js on command prompt)
		//Run in Node.js
		npm install --save react-native-router-flux
 
		//After installing in the Node.js, import inside the project after react components
		import {Actions} from 'react-native-router-flux';
5.Create a class for Form Activity.
One .js file for Log-in Page and One for Sign-in Page.

export default class Form extends Component {
 
}

6.Create constructor with props in Form class
				export default class Form extends Component {
   				constructor(props){        
     			super(props);  //pass props to parent constructor      
     			this.state={            
       			 	email:'',
        			password: ''        
     }   
}

7.Create saveData function in Form
8.Create showData function to show (registered email and password).
9.Add render() function in the form.(To determine if the user click Sign up or Login button.
10.Add CSS Style.
11.Comple the Form Activity.



		

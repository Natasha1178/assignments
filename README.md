# assignments
// ignore: avoid_web_libraries_in_flutter
import 'dart:html';  

import 'package:flutter/material.dart';
void main() {
  runApp(MyApp());
}
class MyApp extends StatelessWidget{
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold( 
        appBar: AppBar(
          title: Center(child: Text("Login Page")),),  
          body: Center(
            child: Column(
              children:[
                SizedBox(height: 30,),
                Container(
                  width: 200,
                  child: TextField(

                    
                ),  
                ), 

              
              SizedBox(height: 30,),
     
                           
              Container(
                  width: 200,
                  child: TextField(

                    
                ),  
                ),  
                SizedBox(height: 30,),
                ElevatedButton(onPressed: (){}, child: Text("Login"))
                  

              ], 
              ),
          )
       
      )  
      ) ;
    
  }
}

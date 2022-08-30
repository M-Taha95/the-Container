"# the-Container" 
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(),
        body: Container(
          decoration: BoxDecoration(
            borderRadius: BorderRadius.all(Radius.circular(50)),
            color: Color.fromARGB(255, 172, 236, 174),
          ),
          padding: EdgeInsets.all(25),
          margin: EdgeInsets.all(20),
          alignment: Alignment.center,
          child: Text("hello flutter students",
              style: TextStyle(
                fontSize: 30,
                color: Color.fromARGB(221, 26, 25, 25),
              )),
          width: double.infinity,
          height: double.infinity,
        ),
      ),
    );
  }
}

import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Text Widget Example'),
        ),
        body: Center(
          child: Text(
            'Welcome to Flutter!',
            style: TextStyle(
              fontSize: 28,
              color: Colors.green,
              fontFamily: 'Roboto', // Custom font family
            ),
          ),
        ),
      ),
    );
  }
}

import 'package:flutter/material.dart';

void main(){
    runApp(const MyApp()):
}

class MyApp extends StatelessWidget{
    const MyApp({super.key});

    @override
    Widget build(BuildContext context){
        return MaterialApp(
        title: 'Flutter Demo',
        theme: ThemData{
        primarySwatch: Colors.blue,
        }
        home: const MyHomePage(title: Flutter Demo Home Page)
        );
    }
}

class MyHomePage extends StatefulWidget{
    const MyHomePage({super.key, required this.title});

    final string title;

    @override
    state<MyHomePage>crateState() =>_MyHomePage();
}

class_MyHomePageState extends State<MyHomePage>{
    int _counter = 0;
    
    void _incrementCounter(){
        setState((
        _counter++;     
        ))
    }
}

@override
Widget build(BuildContext context){
    return Scaffold(
        appBar: appBar(
            title: Text (widget.title),
        )
        body: Center(
            child: Column(
                mainAxisAlignment.center,
                children: <widget>[
                    const Text(
                        'You have pushed the button this many times:',
                    ),
                    Text(
                        '$_counter',
                        style: Theme.of(context).textTheme.headline4,
                    ),
                ],
            ),
        ),
        floatingActionButton: floatingActionButton(
            onPressed: _incrementCounter,
            tooltip: 'Increment',
            child: const Icon(Icons.add),
        ),
    );
}

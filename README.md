# generate-material-theme-for-flutter
Generate Material Theme for Flutter using apppainter

1. First Generate Material color json using apppainer.
2. Run generatevariable.html file
3. Open Json file and copy code of "colorScheme" key all value
4. Press submit button it generate variable of colorScheme code of flutter
5. Put in on file in flutter project
6. Use that variable in main.dart
```
void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: appName,
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        colorScheme: lightColorScheme,
        useMaterial3: true,
      ),
      home: const SplashScreen(),
    );
  }
}
```
- Here `lightColorScheme` is variable of material color

* Download New version App Painter
[AppPainter](https://github.com/zeshuaro/appainter?tab=readme-ov-file)

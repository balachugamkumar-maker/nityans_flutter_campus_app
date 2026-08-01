import 'package:nityans_flutter_campus_app/core/constants/app_routes.dart';
import 'package:nityans_flutter_campus_app/core/theme/app_theme.dart';
import 'package:nityans_flutter_campus_app/presentation/routes/app_router.dart';

void main() {
  WidgetsFlutterBinding.ensureInitialized();
  runApp(const NityansApp());
}

class NityansApp extends StatelessWidget {
  const NityansApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'NityansApp',
      debugShowCheckedModeBanner: false,
      theme: AppTheme.lightTheme,
      darkTheme: AppTheme.darkTheme,
      themeMode: ThemeMode.light,
      initialRoute: AppRoutes.splash,
      onGenerateRoute: AppRouter.generateRoute,
    );
  }
}

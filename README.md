# EcoTrack

Aplicativo Flutter para acompanhamento de hábitos sustentáveis, desenvolvido com arquitetura MVC e gerenciamento de estado via Provider.

---

## Tecnologias

- Flutter ≥ 3.10 / Dart ≥ 3.0
- Provider ^6.1.2

---

## Como executar

```bash
git clone https://github.com/GabrielQueiroz31/ecotrack.git
cd ecotrack
flutter pub get
flutter run
```

---

## Estrutura do projeto

lib/
├── main.dart
├── models/          # Entidades de dados (Habito, AppState, DashboardInfo)
├── controllers/     # Lógica de negócio (HabitoController, NavController, ConfigController)
├── providers/       # EcoProvider — ChangeNotifier central
└── views/
├── screens/     # SplashScreen, HomeScreen, HabitosScreen, DashboardScreen, ConfigScreen
└── widgets/     # HabitoCard, DashboardCard

---

## Protogipagem

- Link do Figma: https://www.figma.com/design/rjIwNMyLD5GnTH1gxHDmMy/EcoTrack---Prot%C3%B3tipo-M%C3%A9dia-Fidelidade?node-id=0-1&p=f&t=lfsJKYdXGYKhbZ8e-0

---

## Funcionalidades principais

- Marcar hábito como concluído (move de pendentes para concluídos)
- Dashboard atualizado automaticamente via Provider
- Navegação por `BottomNavigationBar` e `Drawer`
- Alternância de tema claro/escuro
- Reset dos hábitos ao estado inicial

---

## Widgets utilizados

`Scaffold` · `AppBar` · `Drawer` · `BottomNavigationBar` · `TabBarView` · `ListView` · `GridView`

---

Projeto acadêmico — ADS Senai Americana · 2026
# flutter_http_request_own

Basis:

https://suragch.medium.com/how-to-make-http-requests-in-flutter-d12e98ee1cef

http: ^0.13.4

funktioniert, null safety

ruft http://fluttercrypto.bplaced.net/apps/http/post_req_json.php auf

mit diesen Werten auf:

final json = '{"title": "Hello", "body": "body text", "userId": 1}';

und bekommt das zurück:

flutter: Body: {"title":"Hello","body":"body text","userId":"new UserId"}

Future<void> makePostRequestOwn() async {
funktioniert

Future<void> makePostRequestOwnLibsodium() async {
// not working as bplaced has no libsodium enabled

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

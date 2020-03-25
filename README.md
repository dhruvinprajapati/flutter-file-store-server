[![pub package](https://img.shields.io/pub/v/file_picker.svg)](https://pub.dartlang.org/packages/file_picker)
[![pub package](https://img.shields.io/pub/v/dio.svg)](https://pub.dev/packages/dio#-readme-tab-)
[![Awesome Flutter](https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square)](https://github.com/Solido/awesome-flutter)

# file_picker

File picker plugin alows you to use a native file explorer to load absolute file path from different file types.

# Dio

A powerful Http client for Dart, which supports Interceptors, Global configuration, FormData, Request Cancellation, File downloading, Timeout etc.

## Installation

First, add  *file_picker*,*Dio*  as a dependency in [your pubspec.yaml file](https://flutter.io/platform-plugins/).

```
file_picker: ^1.5.0+2
Dio: ^3.0.9
```

## Api

I am using laravel for Api handling

```
    $file = $request->file('file');

    $extension = $file->getClientOriginalExtension();

    $fullFileName = time(). '.'. $extension;

    $file->storeAs('folderName', $fullFileName,  ['disk' => 'local']);

    return 'uploaded Successfully';
```

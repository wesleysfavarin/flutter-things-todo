# Flutter Things Todo
000
An example Todo App using Flutter with advanced features. :star2:  
Built using Redux architecture and Redux Persist to store redux state.

## UI/UX Concept by Md. Faisal Hossain
Thanks to Md. Faisal Hossain for allowing me to use the ThingsTodo concept.  
Visit his profile for more awesome works!

Uplabs Profile : [Md. Faisal Hossain](https://www.uplabs.com/mdfhossain)  
Things Todo Concept : [Things Todo App](https://www.uplabs.com/posts/freebie-daily-ui-things-todo-app)

## Features
#### Basic
- [x] Add, Edit and Delete Task
- [x] Add, Edit and Delete Category
- [x] Mark as Done, Later and Important
- [x] Sort tasks by date time

#### Filtering
- [x] Daily Task
- [x] Weekly Task
- [ ] Monthly Task
- [x] Done, Later and Important Task
- [x] Search Task

#### Misc
- [ ] Notifications
- [ ] Authentication
- [ ] Settings page

## Application Architecture
The architecture is based off these projects:

- [Redux Sample](https://github.com/brianegan/flutter_architecture_samples/tree/master/example/redux) - [Brian Egan](https://twitter.com/brianegan)
- [inKino](https://github.com/roughike/inKino) - [Iiro Krankka](https://twitter.com/koorankka)
- [Invoice Ninja Flutter Mobile](https://github.com/invoiceninja/flutter-mobile) - [Invoice Ninja](https://github.com/invoiceninja)

## Screenshots
<div style="text-align: center">
  <table>
    <tr>
      <td style="text-align: center">
        <img src="./screenshots/1.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/2.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/3.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/4.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/5.png" width="200" />
      </td>
    </tr>
    <tr>
      <td style="text-align: center">
        <img src="./screenshots/6.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/7.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/8.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/9.png" width="200" />
      </td>
      <td style="text-align: center">
        <img src="./screenshots/5.png" width="200" />
      </td>
    </tr>
  </table>
</div>

## Getting Started

```
git clone https://github.com/nacasha/flutter-things-todo.git
cd flutter-things-todo
flutter packages get
flutter run
```

Run `flutter packages pub run build_runner build` to regenerate file when you made changes on any redux state.

## Packages Used

- `date_utils` to manipulate DateTimes.
- `built_value` and `built_collection` provides Immutable value types and serialization.
- `flutter_redux` and `redux_persist` for state management and persist redux state.
- `flutter_sticky_header` and `flutter_calendar_carousel` for awesome components.
- more at `pubspec.yaml`

### Star the repo :star: to support the project or follow me. Thanks! :heart:

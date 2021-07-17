# MovieLix

- [MovieLix](#movielix)
  - [Architecture](#architecture)
    - [Firestore](#firestore)
  - [Users](#users)
  - [GitFlow](#gitflow)

## Architecture

This project contains three main components:

- The backend ([Linode](./linode.md)): our server implemented in `Python`.
- The [App](./app.md): our application implemented in `Android`.
- `Firestore`: Google's realtime database for storing all the information.

This diagram shows our architecture:

<p align="center">
    <img src="Diagrams/out/backend/backend.png"/>
</p>

### Firestore

We store all the stuff in `Firestore`, which will contain the following collections.

## Users

The authentication process is handled by [Firebase](https://firebase.google.com/).

## GitFlow

In this project we follow the `GitFlow` workflow:

![GitFlow](https://i.pinimg.com/originals/d6/06/ac/d606ac0eca71d6ead76c73d7aa08d51b.png)

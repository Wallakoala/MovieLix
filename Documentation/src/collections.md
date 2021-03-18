# Collections

## users

We need to store extra information about the users. That information cannot be stored __Firebase__, so we need to use __Firestore__:

| Fields      |  Type  | Nullable | Notes                 |
| ----------- | :----: | :------: | :-------------------- |
| id          | String |    ❌     | Taken from `Firebase` |
| name        | String |    ❌     | Taken from `Firebase` |
| photo_url   | String |    ✔️     | Taken from `Firebase` |
| num_reviews | Number |    -     |                       |

## movies

Collection to store all the movies retrieved by __Linode__. Field names are just numbers to reduce data usage.

| Fields |      Type       | Nullable | Notes          |
| ------ | :-------------: | :------: | :------------- |
| 2      |     String      |    ❌     | Title          |
| 3      |     Number      |   TBD    | Year           |
| 4      |     String      |    ✔️     | Summary        |
| 5      |     Number      |    ❌     | Duration       |
| 6      |     Number      |    ✔️     | IMDB's Rating  |
| 8      |     String      |    ❌     | Image          |
| 9      | Array of String |    ✔️     | List of genres |
| 10     |     String      |    ✔️     | PG Rating      |

## reviews

Collection to store the users' reviews.

| Fields    |  Type  | Nullable | Notes |
| --------- | :----: | :------: | :---- |
| movie     | String |    ❌     |       |
| score     | String |    ❌     |       |
| user      | String |    ❌     |       |
| timestamp | String |    ❌     |       |
| comment   | String |    ✔️     |       |

## friends

Collection to store the users' friends.

| Fields    |      Type       | Nullable | Notes |
| --------- | :-------------: | :------: | :---- |
| id        |     String      |    ❌     |       |
| friend_of | Array of String |    ❌     |       |

## followers

Collection to store the users' followers.

| Fields      |      Type       | Nullable | Notes |
| ----------- | :-------------: | :------: | :---- |
| id          |     String      |    ❌     |       |
| followed_by | Array of String |    ❌     |       |

---

<p align="center">
    <img src="Diagrams/out/firestore/firestore.png"/>
</p>

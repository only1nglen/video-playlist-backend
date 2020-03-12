# VideoPlaylist API

An API for VideoPlaylist created with Express and React
Users can create, edit, and delete their videos

[VideoPlaylist Repo](https://github.com/only1nglen/video-playlist-client)

[VideoPlaylist](https://only1nglen.github.io/video-playlist-client/)

## API URL

```js
production: 'https://ancient-peak-54308.herokuapp.com'
development: 'http://localhost:4741'
```

## API End Points

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out`            | `users#signout`   |
| PATCH  | `/change-password`     | `users#changepw`  |
| GET    | `/videos`              | `videos#index`    |
| POST   | `/videos`              | `videos#create`   |
| SHOW   | `/videos/:id`          | `videos#show`     |
| PATCH  | `/videos/:id`          | `videos#update`   |
| DELETE | `/videos/:id`          | `videos#destroy`  |

## ERD

[ERD](https://imgur.com/bj7DFJr)

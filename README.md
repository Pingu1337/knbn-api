# knbn-api

> Backend repo for https://knbn.zip

🌐 [Live](https://knbn.zip) \
🏞 [Frontend](https://github.com/Pingu1337/knbn-ui)


Knbn is a super simple kanban app built with rust & sveltekit.
It features a personal kanban without having to create an account or register in any way.

 When you "log in" you get a random UID, you can also choose to "log in" with a custom user code. 
 *Note that this is not guaranteed to be unique so if you choose the code `1` chances are someone else might select it as well.*

> Tasks are not private in any way other than locked behind the user code, so do not share any personal or sensitive information.


---

## Prerequisites

- [rust/cargo](https://www.rust-lang.org/learn/get-started)
- *(optional)* [docker](https://www.docker.com/get-started/)
- *(optional)* local instance of [redis](https://hub.docker.com/r/redis/redis-stack)


## Running the project

```bash
# build the backend
cargo build

# Start the backend
cargo run
```

## Contribute 

- **[Create Issue](https://github.com/Pingu1337/knbn-api/issues/new)** 
- **[Create Pull Request](https://github.com/Pingu1337/knbn-api/compare)**
#### Useful links
- [conventional commits](https://www.conventionalcommits.org/)

## License

[MIT](LICENSE)
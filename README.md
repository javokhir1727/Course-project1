# Course-project1

# Javokhir Makhamov’s ITPU Course Project

## Progress report

| Tasks                  | Start Date | End Date  |
|------------------------|------------|-----------|
| Gathering requirements | 14-May-23  | 22-May-23 |
| Entity Design          | 23-May-23  | 27-May-23 |
| Data Access Layer      | 30-May-23  | 1-June-23 |
| Service Layer          | 3-June-23  | 5-June-23 |
| Controller Layer       | 6-June-23  | 8-June-23 |

## Screenshot from the interactive console

<div style="display: flex; flex-wrap: wrap">
<div align="center">
  <img src="image/Console11.png?raw=true" width="90%" height="auto"/>
  <img src="image/Console22.png?raw=true" width="90%" height="auto"/>
</div>
</div>


## Getting Started
To get started with this project, follow these steps:

- Clone the repository to your local machine.
- Install in pom.xml file.
- Run the application using your IDEA's run button on Main class.
- Console window will be opened.
- you can play around with this interactive console to retrieve all inventories or by their parameters;

## Features
This project includes the following features:

- Parsing inventories (Bedclothing and Dish .csv files)
- Mapping parsed Strings from .csv files to the corresponding DTO entities
- Retrieve all inventories
- Retrieve all inventories by color and inventory type
- Retrieve all inventories by price (min, max) and inventory type

## Testing
- Dish and Bedclothing mapRow methods - unit tested
- Inventory DAO methods - unit tested

## Technologies Used
This project was built using the following technologies:

- Java 17.0.2
- GitHub
- com.opencsv 5.7.1

👤 **Javokhir Makhkamov**

- GitHub: [javokhir1727](https://github.com/javokhir1727)
- Facebook: [JavokhirMakhkamov](https://twitter.com/javokhir.makhkamov)


## Contributing
If you would like to contribute to this project, please follow these steps:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and commit them.
- Push your changes to your fork.
- Submit a pull request.

## License
This project is [MIT](./MIT.md) licensed.

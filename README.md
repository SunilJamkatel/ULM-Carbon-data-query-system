# ULM Carbon Data Query System

This is a carbon query data system built by Sunil Jamkatel for Dr. Joydeep Bhattacharjee and his plant Ecology lab. 

![Index Page](https://i.imgur.com/O70fQg8.jpg)

## Getting Started

To get started with this, you would have to clone this repository in your disk. 

### Prerequisites

Download github bash or download the zip copy of the project. You need to have nodejs and mysql workbench installed on your local machine as well.

```
node --version
v11.5.0

npm --version
6.4.1
```

### Installing

Downloading the files to your system using git

```
git clone https://github.com/SunilJamkatel/ULM-Carbon-data-query-system.git
```

After that, cd to your project directory

```
cd ULM-Carbon-data-query-system/
```

### Install the required dependencies

Install the required dependencies using
```
npm install
```


## Checking the database connection

Make sure you run the fluxdatabase.sql file after installing mysql workbence on your machine or else the program would not load.


## Running the app

Run the app using the command
```
npm start
```

If everything runs fine, the following output will be displayed

```
> flux@1.0.0 start D:\cs\ULM-Carbon-data-query-system
> node app.js

Server has started!
MySql Connected!!
```

## Deployment

Choose the web browser of your choice and navigate to localhost.

## Functionalities

* Query data in a single day
![Single Day Query](https://i.imgur.com/LVe6oDi.jpg)

* Query a range of data in between different dates
![Range Day Query](https://i.imgur.com/Muf5SoQ.jpg)

* Choose only the data column you need
![Range Day Query](https://i.imgur.com/WDJ2tIR.jpg)

* Upload csv to the database
![Upload CSV](https://i.imgur.com/bu05xjG.jpg)

* Download custom queries as a csv file
![Save CSV file](https://i.imgur.com/ayNAuXf.jpg)

## Built With

* [Materialize](https://github.com/Dogfalo/materialize) - The web framework used

## Contributing

Please send me an email at [hello@suniljamkatel.me](mailto:hello@suniljamkatel.me) if you need additional help with setting up the app.


## Authors

* **Sunil Jamkatel** - *Initial work*

See also the list of [contributors](https://github.com/SunilJamkatel/ULM-Carbon-data-query-system/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

# MongoDB-Log-Plotter

MongoDB-Log-Plotter is a script that analyzes MongoDB logs (version 4.4 or above) to extract information about slow queries, connections, and errors. It then visualizes the data using Dash and Plotly.

## Prerequisites
- Python 3.10
- MongoDB version 4.4 or above
- Install dependencies using `pip install -r requeriments.txt`

## Installation
1. Clone the repository: `git clone https://github.com/hcymysql/MongoDB-Log-Plotter.git`
2. Navigate to the project directory: `cd MongoDB-Log-Plotter`
3. Install dependencies: `pip3 install -r requeriments.txt -i "http://mirrors.aliyun.com/pypi/simple" --trusted-host "mirrors.aliyun.com"`
4. Run the script: `python3 MongoDB_log_plotter.py /data/mongodb/mongodb5_0/logs/mongod1.log`

## Usage
Run the script with the path to the MongoDB log file as a command-line argument. 
```bash
python3 MongoDB_log_plotter.py /data/mongodb/mongodb5_0/logs/mongod1.log
```

The script will launch a server, and you can view the dashboard by navigating to [http://localhost:8050/](http://localhost:8050/) in your web browser:

![Screenshoot](https://github.com/zelmario/MongoDB-Log-Plotter/blob/main/screenshot1.png?raw=true)


You can zoom, pan, and filter the namespaces and erros.
Also, if you click on a data point, the command used is displayed

## MongoDB Version Compatibility
MongoDB-Log-Plotter is designed to work with MongoDB version 4.4 or above.

## Features
- Plot slow queries, connections, and errors from MongoDB logs
- Visualize data using Dash and Plotly
- Display additional information about the MongoDB environment


## License
This project is licensed under the GNU License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Since I'm not a programmer, your feedback is valuable. If you are a programmer and notice any mistakes or want to enhance the script, please feel free to contribute! :)



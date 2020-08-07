# Forecasting Beijing air quality through prediction of PM2.5 measurements using time-series data

Setting up
------------
- Install following packages in python path before executing python files

	- ***tensorflow***
	- ***numpy***
  - ***sklearn***
  - ***pandas***
  - ***seaborn***
  - ***matlplotlib***
  

### Copy following files into project folder
	BeijingAirQualityForecast.py
  
### Program Execution

- Program accepts time steps(--ts or -t), train rate (--tr or -r), epochs(--ep or -e) & batch size(--bs or -s) as arguments

		python BeijingAirQualityForecast.py --ts <time_steps> --tr <train_rate> --ep <epochs> --bs <batch_size>
		
                                            OR
    
		python BeijingAirQualityForecast.py -t <time_steps> -r <train_rate> -e <epochs> -s <batch_size>
    
    For Eg: 
    
		python BeijingAirQualityForecast.py --ts 20 --tr 0.5 --ep 10 --bs 140
		
                                            OR
    
		python BeijingAirQualityForecast.py -t 20 -r 0.5 -e 10 -s 140

- Default Values

		time_steps = 10
		train_rate = 0.7
		epochs = 10
		batch_size = 128



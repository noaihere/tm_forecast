# tm_forecast

**Steps to install packages and run notebook**
1. Navigate to windows cmd directory where tm_forecast folder is cloned
2. conda create -n myenv 
3. conda activate myenv
4. pip install -r requirements.txt

**For geohash library to work**
1. issue command  *pip install geohash*
2. note down path where geohash is stored 
3. navigate to path. 
4. rename folder as geohash rather than Geohash
5. in folder, in init.py file, add a dot so it becomes 'import from .geohash'

**Launch notebook that trains model**
1. navigate to path tm_forecast folder is
2. issue command *juypter notebook*
3. run notebook data_exploration_final

**Launch notebook to test data**
1. navigate to path tm_forecast folder is
2. issue command *juypter notebook*
3. add test data entitled 'test.csv' with same format as 'training.csv'
4. run notebook test_data_final

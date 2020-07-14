# API

## DataGetter

### read_data_from_csv
```
pd.read_csv("data.csv")
```

| Method Description | This method will be used to read data from a csv file or a flat file |
|--------------------|----------------------------------------------------------------------|
|Input parameter     |names	self,file_name, header,names, use_cols, separator               |
|Input Parameter Description |	- file_name: name of the file to be read|
||								- header: Row number(s) to be used as column names
||								- names : array-like, optional
||							- List of column names to use. If file contains no header row, then you should explicitly pass ``header=None``.
||						- Use_cols:  To load a subset of columns
||					- Separator: Delimiter to use
|Output			 |A pandas Dataframe                                                    |
|On Exception	     |Write the exception in the log file. Raise an exception with the appropriate error message|



### read_data_from_html

``` 
pd.read_html("www.google.com")
```

| Method Description | This method will be used to read data from an HTML web page |
|--------------------|----------------------------------------------------------------------|
|Input parameter     |self,url              |
|Input Parameter Description |	- url: URL of the HTML page to be read. |
|Output			 |A pandas Dataframe                                                    |
|On Exception	     |Write the exception in the log file. Raise an exception with the appropriate error message|

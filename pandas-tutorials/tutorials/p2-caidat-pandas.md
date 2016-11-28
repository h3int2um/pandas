# Cài đặt Pandas trên Ubuntu 16.04

Thực hiện: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 28 tháng 11 năm 2016

## Tài liệu tham khảo

[Data Analysis with Python and Pandas Tutorial Introduction](https://pythonprogramming.net/data-analysis-python-pandas-tutorial-introduction/).

## Cách cài đặt

* Cài đặt Pandas trên Ubuntu 16.04:	

	+ Mở cửa sổ Terminal (nhấn `Ctrl + Alt + T`), gõ lệnh sau để cài đặt `python-pip` 
	(nếu đã cài đặt rồi thì bỏ qua bước này):
	
			$ sudo apt-get install python-pip
			
		![](https://raw.githubusercontent.com/h3int2um/pandas/master/pandas-tutorials/images/caidat-python-pip-ubuntu.png)

	+ Tiếp tục gõ lệnh sau trong cửa sổ Terminal để cài đặt `Pandas`:
	
			$ sudo pip install pandas
			
		![](https://raw.githubusercontent.com/h3int2um/pandas/master/pandas-tutorials/images/caidat-pandas-ubuntu.png)
		
	+ Kiểm tra cài đặt: gõ các lệnh sau, nếu không báo lỗi nghĩa là cài đặt thành công. 
	Trong trường hợp này phiên bản cài đặt là `0.19.1`.
	
			$ python
			
			>>> import pandas
			
			>>> pandas.__version__
			
			u'0.19.1'
		
		![](https://raw.githubusercontent.com/h3int2um/pandas/master/pandas-tutorials/images/kiemtra-caicat-pandas.png)

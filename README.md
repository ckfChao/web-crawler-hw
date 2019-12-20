# web-crawler-hw
It is a web crawler coding with python.
  ## Member
  > - :baby: B08902087 [Chao Kin Fong](https://github.com/ckfChao)
  > - :baby: B08902111 [Sun Tzu Hsiang](https://github.com/Raito411)
  ## Environment
  - Windows10, python 3.6.6, lxml==4.4.2, requests==2.22.0
  ## How to run the program
  ```
  python3 main.py --start-date [start date] --end-date [end date] --output [out filename]
  ```
  - ```--start-date``` and ```--end-date``` will be in the format of ```[Year]-[month]-[day]```. For instance, ```2019-12-09```.
  - ```--output``` is the csv filename to save. For instance, ```output.csv```.
# Intro
  The program is a web crawler. It will fetch titles, dates and relative urls from tables in [https://www.csie.ntu.edu.tw/news/news.php?class=101](https://www.csie.ntu.edu.tw/news/news.php?class=101).
  After that, It will fetch the contents from the relative urls. Finally, It will write the dates, titles and contents to the output file.

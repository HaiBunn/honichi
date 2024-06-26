# honichi
## README

### 程序简介

此程序旨在从指定URL下载CSV文件，并根据用户输入的月份和年份，计算并输出对应月份的总访问量。

### 使用方法

1. **下载程序:** 您可以将此代码保存为Python文件（例如 `total_visitors.py`）。
2. **运行程序:** 在命令行中，使用以下命令运行程序：

```bash
python total_visitors.py
```

3. **输入信息:** 程序会提示您输入要查找的月份缩写和年份。输入信息后，程序将开始处理。
4. **查看结果:** 程序会输出指定月份的总访问量。如果找不到数据，则会提示未找到相关数据。

### 注意

* 此程序假设CSV文件具有以下列：
    * Country/Area
    * Month (abbr)
    * Year
    * Visitor Arrivals
    * Growth Rate(%)
* 如果您的CSV文件具有不同的列，则需要相应地修改程序。
* 此程序使用 `requests` 库来下载CSV文件。如果您没有安装此库，则可以使用以下命令安装它：

```bash
pip install requests
```

### 运行示例

```
请输入要查找的月份缩写：Jan
请输入要查找的年份：2020
2020年Jan月的总访问量为：458,000
```

## README (English)

### Program Overview

This program aims to download a CSV file from a specified URL and calculate the total number of visitors for a given month based on user input.

### Usage

1. **Download the program:** You can save this code as a Python file (e.g., `total_visitors.py`).
2. **Run the program:** In the command line, run the program using the following command:

```bash
python total_visitors.py
```

3. **Enter information:** The program will prompt you to enter the month abbreviation and year you want to look for. Once you enter the information, the program will start processing.
4. **View results:** The program will output the total number of visitors for the specified month. If no data is found, it will prompt that no data was found.

### Notes

* This program assumes the CSV file has the following columns:
    * Country/Area
    * Month (abbr)
    * Year
    * Visitor Arrivals
    * Growth Rate(%)
* If your CSV file has different columns, you will need to modify the program accordingly.
* This program uses the `requests` library to download the CSV file. If you do not have this library installed, you can install it using the following command:

```bash
pip install requests
```

### Example Run

```
Enter the month abbreviation to find: Jan
Enter the year to find: 2020
Total number of visitors for Jan 2020: 458,000
```


## README（日本語）

### プログラム概要

このプログラムは、指定されたURLからCSVファイルをダウンロードし、ユーザーが入力した月と年に基づいてその月の総訪問者数を計算し、出力します。

### 使い方

1. **プログラムのダウンロード:** このコードをPythonファイルとして保存します（例：`total_visitors.py`）。
2. **プログラムの実行:** コマンドラインで、以下のコマンドを使用してプログラムを実行します。

```bash
python total_visitors.py
```

3. **情報の入力:** プログラムは、調べたい月略語と年を入力するように促します。情報を入力すると、プログラムは処理を開始します。
4. **結果の閲覧:** プログラムは、指定された月の総訪問者数を表示します。データが見つからない場合は、データが見つからないことを示すメッセージが表示されます。

### 注意事項

* このプログラムは、CSVファイルが以下の列を持つことを前提としています。
    * Country/Area
    * Month (abbr)
    * Year
    * Visitor Arrivals
    * Growth Rate(%)
* CSVファイルの列が異なる場合は、プログラムを適宜修正する必要があります。
* このプログラムは、`requests`ライブラリを使用してCSVファイルをダウンロードします。このライブラリがインストールされていない場合は、以下のコマンドを使用してインストールできます。

```bash
pip install requests
```

### 実行例

```
調べたい月略語を入力してください：Jan
調べたい年を入力してください：2020
2020年1月の総訪問者数：458,000
```



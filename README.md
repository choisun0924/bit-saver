# Bit-Saver

Bit-Saver is a Python library for fetching and saving OHLCV (Open, High, Low, Close, Volume) data from Upbit exchange to local storage.

## Installation

You need to have Python 3 or higher installed. Installation of the library can be done simply with pip:

```
pip install bit-saver
```

## Usage

Here's a basic example of how to use Bit-Saver:

```python
from bit_saver import BitSaver

bit_saver = BitSaver()
bit_saver.save_all_data(datetime(2017, 9, 24, 9, 0, 0), datetime.now(), 'your_directory_path')

```

```python
from bit_saver import BitSaver

bit_saver = BitSaver()
bit_saver.save_single_ticker_data('KRW-BTC', datetime(2020, 1, 1, 0, 0, 0), datetime.now(), 'your_directory_path')
```

## Features
- Fetches daily OHLCV data for all cryptocurrencies from Upbit.
- Fetches daily OHLCV data for a specific cryptocurrency from Upbit.
- Fetches and saves data within a user-specified date range.
- Saves the fetched data locally in CSV format.

## License
This project is distributed under the MIT license. For more information, see the LICENSE file.

## Author
Bit-Saver was created by Choi Sun, an AI researcher from South Korea born in 1997. He developed this project as a personal endeavor and not for any commercial purposes. You can reach him at choisun@tritech.co.kr and learn more about his work at Tritech.

## Contact
If you encounter any problems or have any questions, please open an issue on our Github issues page.

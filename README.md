# bitcoin-price-forecasting
Final ML project forecasting Bitcoin price using MLP and LSTM models.

## What is this project about?
Forecasting Bitcoin's next-day closing price using two deep learning 
models; a Multi-Layer Perceptron (MLP) and an LSTM network and 
comparing which handles time series data better.

## What files are included?
- bitcoin_forecasting.ipynb — main notebook with all code
- Bitcoin_Daily.csv — daily Bitcoin price dataset (2019–2023)

## What did I learn?
LSTM outperformed MLP because it can process data in sequence, while 
MLP treats all 30 days as unordered inputs. I also learned how important 
chronological train/test splitting is for time-series problems.

## Author
Beryl Abi Ouma

One reminder from the sheet, worth repeating: don't upload API keys, passwords, or personal info — your files here are fine (just code + public price data), so you're safe.

Want me to help you write the actual README content as a ready-to-paste block, or tweak anything above?

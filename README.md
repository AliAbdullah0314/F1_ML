# Formula 1 Race Outcome Predictor

A machine learning project that predicts Formula 1 lap times and race outcomes using LSTM neural networks and historical F1 data from 2014-2023.

## Project Overview

This project leverages advanced machine learning techniques to predict Formula 1 race outcomes by analyzing:
- Individual driver lap times
- Race conditions and strategies
- Historical driver and team performance
- Track characteristics

The model has demonstrated remarkable accuracy, achieving:
- Precise podium predictions for the 2024 Bahrain Grand Prix
- Accurate top 5 finish predictions across multiple races

## Key Features

**Data Processing**
- Comprehensive dataset spanning 203 races and 55 drivers
- Over 214,000 individual lap records
- Integration of multiple data sources including Ergast API and FastF1

**Model Architecture**
- Primary LSTM-based prediction model
- Custom loss function incorporating:
  - Lap time accuracy
  - Position prediction
  - Historical performance metrics

**Prediction Capabilities**
- Real-time lap time forecasting
- Race position predictions
- Performance trend analysis

## Technical Implementation

**Core Components**
- PyTorch for LSTM implementation
- Custom scalers for data normalization
- Early stopping mechanism with 50 epochs
- Multiple LSTM layers with dropout for optimal performance

## Results

The model has shown exceptional performance in predicting race outcomes:

| Race | Correct Winner | Podium Matches | Top 5 Matches |
|------|---------------|----------------|---------------|
| 2024 Bahrain GP | Yes | 3/3 | 5/5 |
| 2024 Abu Dhabi GP | Yes | 3/3 | 4/5 |


## Future Development

- Implementation of transformer models
- Extended prediction scope including:
  - Pit stop strategy optimization
  - Safety car predictions
  - Weather impact analysis

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for improvements and bug fixes.

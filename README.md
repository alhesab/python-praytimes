## PrayerTimes
User's Manual:
http://praytimes.org/manual

Calculation Formulas:
http://praytimes.org/calculation

## Usage

```python
    >>> PT = PrayTimes('ISNA')
    >>> times = PT.getTimes((2011, 2, 9), (43, -80), -5)
    >>> times['sunrise']
    07:26
```

## Interface

```python
    getTimes (date, coordinates, timeZone [, dst [, timeFormat]])

    setMethod (method)       // set calculation method
    adjust (parameters)      // adjust calculation parameters
    tune (offsets)           // tune times by given offsets

    getMethod ()             // get calculation method
    getSetting ()            // get current calculation parameters
    getOffsets ()            // get current time offsets
```

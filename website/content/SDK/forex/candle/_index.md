## Get underlying data 
### forex.candle(data: pandas.core.frame.DataFrame, to_symbol: str = '', from_symbol: str = '', ma: Optional[Iterable[int]] = None, external_axes: Optional[List[matplotlib.axes._axes.Axes]] = None)

Show candle plot for fx data.

    Parameters
    ----------
    data : pd.DataFrame
        Loaded fx historical data
    to_symbol : str
        To forex symbol
    from_symbol : str
        From forex symbol
    ma : Optional[Iterable[int]]
        Moving averages
    external_axes: Optional[List[plt.Axes]]
        External axes (1 axis is expected in the list), by default None

FinAnSu
=======

<table>
  <tr>
    <th>Homepage</th>
    <td><a href="http://brymck.herokuapp.com">brymck.herokuapp.com</a></td>
  </tr>
  <tr>
    <th>Author</th>
    <td>Bryan McKelvey</td>
  </tr>
  <tr>
    <th>Copyright</th>
    <td>(c) 2010-2012 Bryan McKelvey</td>
  </tr>
  <tr>
    <th>License</th>
    <td>MIT</td>
  </tr>
</table>

FinAnSu aims to provide user-friendly tools for use in financial applications.
The add-in is in its development stages, but it currently offers:

  * Live, streaming [web import](http://code.google.com/p/finansu/wiki/WebData
    capabilities) (Excel 2002+), including custom functions for easily
    [importing security prices](http://code.google.com/p/finansu/wiki/Quotes)
    from Bloomberg.com, Google Finance and Yahoo! Finance
  * Functions that can [parse
    CSVs](http://code.google.com/p/finansu/wiki/WebData#ImportCSV on the web,
    including custom functions to easily import stock quote data from [Google
    Finance](http://code.google.com/p/finansu/wiki/Quotes#GoogleHistory)
    and instrument data from the [Fed H.15
    release](http://code.google.com/p/finansu/wiki/Quotes#H15History) (yields
    for Fed Funds, commercial paper, Treasuries, interest-rate swaps, etc.).
  * Basic options pricing, including
    [Black-Scholes](http://code.google.com/p/finansu/wiki/BlackScholes),
    [the options Greeks](http://code.google.com/p/finansu/wiki/Greeks)
    and [a few more complex options
    models](http://code.google.com/p/finansu/wiki/AmericanBermudan)
  * A bit on [FRAs](http://code.google.com/p/finansu/wiki/FRAs) (forward rate
    agreements)
  * A continuously compounded rate
    [interpolator](http://code.google.com/p/finansu/wiki/Interpolation) (need to
    add more: linear, cubic, cubic spline, etc.)
  * A Federal Reserve holiday calculator (need to add more for different
    calendars, as well as roll date conventions)
  * A handful of tools for converting between discount factors and forward rates
  * Function to [automatically sort
    ranges](http://code.google.com/p/finansu/wiki/Sorting) that contain rows and
    columns of data
  * Some formatting macros for
    [currencies](http://code.google.com/p/finansu/wiki/Currencies) and [a few
    layout options](http://code.google.com/p/finansu/wiki/Layout) that aren't
    easily accessible in Excel

Requirements
------------

Currently, this works with 32- and 64-bit versions of **Windows**, but it
requires a **32-bit version of Excel** (2003+ for best results). I'm looking
into improving 64-bit support.

The add-in also requires [.NET 4](http://www.microsoft.com/net).

Installation
------------

1. Download the current version of FinAnSu on my [GitHub downloads
   page](https://github.com/brymck/finansu/downloads)
2. Unzip it to a temporary directory
3. Run the `install.bat` script

In Action
---------

![FinAnSu in action](https://github.com/brymck/finansu/raw/master/img/quote.gif)

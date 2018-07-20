**Overview**

Essential Studio for Xamarin contains all the necessary user interface components like datagrids, charts and gauges that are needed to build typical line of business mobile applications. User interface elements like the charts and gauges can be configured in a common view using C# or XAML and it gets rendered as native controls on the respective platforms without any additional work.

This suite also includes a powerful set of components for manipulating Microsoft Excel, Microsoft Word and Adobe PDF file formats. All the file format components have a feature rich API that exposes most of the functionality that the underlying file format itself has to offer.

Here is the complete list of all the components that ship with Essential Studio for Xamarin

**Grid**

  [__DataGrid__](#DataGrid)

**Data Visualization**

  [__Chart__](#Chart)

  [__DateTime RangeNavigator__](#DateTimeRangeNavigator)
  
  [__Schedule__](#Schedule)

  [__CircularGauge__](#CircularGauge)
  
  [__DigitalGauge__](#DigitalGauge)
  
  [__LinearGauge__](#LinearGauge)

  [__TreeMap__](#TreeMap)
  
  [__Maps__](#Maps)
  
  [__Barcode__](#Barcode)

**File Format**

  [__XlsIO__](#XlsIO)

  [__DocIO__](#DocIO)

  [__PDF__](#PDF)

**Editors**

  [__RangeSlider__](#RangeSlider)
  
  [__AutoComplete__](#AutoComplete)
  
  [__NumericTextBox__](#NumericTextBox)
  
  [__Calendar__](#Calendar)
  
  [__Rating__](#Rating)

**Notifications**

  [__BusyIndicator__](#BusyIndicator)

#<a id="DataGrid"></a>DataGrid

The Essential DataGrid for Xamarin is a high performance grid component that has been built to achieve the best possible performance on the Xamarin platform. It offers smooth and responsive touch, scrolling up to hundreds of thousands of records. The Essential DataGrid includes several advanced features like grouping, sorting, filtering, etc. as follows:

**Data Sources**

The Essential DataGrid works out of the box for all the popular DataSources. The DataGrid can automatically generate columns for the properties in the data model.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/DataVirtualization.png)

**Sorting**

The DataGrid allows the end users to sort data against any column by touching the Header or by adding SortColumnDescription in code. Sorting in each column iterates through three sort states; ascending, descending, and unsorted. Custom sorting logic is also supported.

The DataGrid supports Multicolumn sorting. It can be initiated by setting the AllowMultiSort property and clicking on multiple column headers against which the data is to be sorted.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Sorting.png)
![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/CustomSorting.png)

**Grouping**

The DataGrid offers grouping by adding GroupColumnDescription in code. The DataGrid can calculate and display summary information in the caption for each group. Custom grouping logic is also supported.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Grouping.png)
![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/CustomGrouping.png)

**Filtering**

The Datagrid can easily be filtered by setting Predicate to the View.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Filtering.png)

**Selection**

The DataGrid provides explicit support for row-based selection upon touching the rows. The row selection has Single, Multiple, SingleDeselect and None modes. The SingleDeselect mode lets you deselect the selected row upon touching it again.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Selection.png)

**Template Column**

The DataGrid provides support for Template column using which any controls can be hosted inside the GridCell.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/RenderingDynamicData.png)
![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/celltype.png)

**SwipeButtons**

The DataGrid control supports swiping of rows. Swipe buttons are displayed when a user swipes from left to right or from right to left over a data row. Create swipe templates and associate the views in it with custom actions.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/SwipeButtons.png)

**LoadMore**

The DataGrid control provides support for loading a subset of data to its data source in the runtime using LoadMore view. It also allows you to customize the LoadMore view and their positions to either top or bottom based on the requirements.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/LoadMore.png)

**PullToRefresh**

The DataGrid control provides support for refreshing the data source in the runtime when performing the pull to refresh action. It also allows you to customize the PullToRefresh view based on the application requirements.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/PullToRefresh.png)

**Paging**

The Datagrid control provides built-in options to page the data on demand when dealing with large volumes of data.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Paging.png)

**Conditional Styles**

The DataGrid provides extensibility to customize the CellStyle using which styles can be applied for a column based on conditions.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/ConditionalStyling.png)

**Styles**

The Datagrid control provides support for styles. It also allows you to customize the styles to display the data visually appealing based on the application requirements. This greatly enhances the appearance of the grid and provides better user experience.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Style.png)

**Exporting**

The DataGrid control provides support for exporting the data to Excel and Pdf with several customization options like custom appearance, excluding specific columns, excluding headers, setting custom row height, setting custom column width, etc.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/Exporting.png)

**Freeze Panes**

The DataGrid has added support to freeze rows in the View.

![datagrid]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/datagrid/Forms/FrozenRow.png)

**RowHeight Customization**

The DataGrid control provides support to change the height of the row based on the content of any column or certain columns to enhance the readability of the content.

|  |
| --- |
|  |

#<a id="Chart"></a>Chart

Essential Chart for Xamarin.Forms is a visually stunning charting component that is also easy to use. It includes all the common chart types ranging from line charts to financial charts.

**Chart Types**

22 chart types can be plotted including Line, Fast Line, Spline, Column, Range Column, Scatter, Area, Spline Area, Bar, Pie, Doughnut, Pyramid, Funnel, Bubble, Candle, OHLC, Stacking Column, Stacking Bar, Stacking Area, Stacking Column 100, Stacking Bar 100 and Stacking Area 100..

**Column Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/column.png)

**Line Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/line.png)

**Spline Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/spline.png)

**Step Line Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stepline.png)

**Spline Area Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/splinearea.png)

**Area Series**

![chart]( http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/area.png)

**Scatter Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/scatter.png)

**Range Column Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/rangecolumn.png)

**Bar Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/bar.png)

**Pie Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/pie.png)

**Doughnut Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/doughnut.png)

**Pyramid Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/pyramid.png)

**Funnel Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/funnel.png)

**Bubble Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/bubble.png)

**Stacking Area Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stackingarea.png)

**Stacking Area 100 Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stackingarea100.png)

**Stacking Bar Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stackingbar.png)

**Stacking Bar 100 Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stackingbar100.png)

**Stacking Column Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stackingcolumn.png)

**Stacking Column 100 Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stackingcolumn100.png)

**Candle Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/candle.png)

**OHLC Series**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/ohlc.png)

**Axis**

Essential Chart has several specialized axis types including NumericalAxis, CategoryAxis, DateTimeAxis and LogarithmicAxis. Several aspects of the axis like position, labels appearance, gridlines and ticks can be customized.

**Numeric Axis**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/numericaxis.png)

**Category Axis**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/categoryaxis.png)

**Date Time Axis**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/datetimeaxis.png)

**Logarithmic Axis**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/logarithmicaxis.png)

**Zooming and Panning**

Chart provides you an option to zoom and pan. Using this feature you can clearly view the large amount of data points.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/zoom1.png)

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/zoom2.png)

**Data Point Selection**

Chart allows you to select a data point in the series.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/selection.png)

**Tooltip**

Tooltip is used to display any information over a chart series. 

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/tooltip.png)

**Trackball**

Trackball feature used to see the data point near the finger.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/trackball.png)

**Strip Line**

The Chart control supports strip lines to classify different regions in the chart area using colors and text annotations.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/stripline.png)

**Vertical Chart**

Chart allows you to change the orientation of the series, which provides different perception on the data.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/verticalchart.png)

**Data Marker Label**

Data points can be easily annotated with labels to indicate its measure and dimension thereby improving the readability of a data. Data labels can be positioned elegantly based on the series types. Overlapping labels can be realigned with respect to available space in a circular series, such as pie and doughnut charts.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/labelangle.png)

**Auto Scrolling**

Chart will automatically scroll to display a fixed range of data points. You can also pan to view previous data points.

**Custom Object**

You can set any custom objects as an ItemsSource for Chart.

**Export the Chart as an Image**

You can save the chart as an image in picture gallery.

**Flexible label positioning**

The position of axis labels can be fully customized to provide better readability and to avoid any potential overlap.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/labelrotation.png)

**Automatic range calculation with range padding**

Optimal ranges are automatically calculated based on the given data; the calculated ranges can also be customized using range padding.

**Range Padding – None**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/rangepaddingnone.png)

**Range Padding - Round**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/rangepaddinground.png)

**Range Padding - Additional**

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/rangepaddingadditional.png)

**Multiple Axes**

Data can be plotted against multiple scales in a single chart.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/multipleaxis.png)

**Interactive Legends**

Legends can be positioned anywhere within the chart area. It is also possible to toggle the visibility of specific series by tapping on the legend items. This functionality is very useful when the user needs to focus on the data in specific series only.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/legend.png)

**High Performance**

Essential Chart has been built from the ground up to handle large volumes of data. It can easily render thousands of data points within a second.

![chart](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/chart/performance.png)

|  |
| --- |
|  |

#<a id="DateTimeRangeNavigator"></a>DateTime RangeNavigator

SfDateTimeRangeNavigator is a time based data visualization control. Its rich interface allows you to visualize and select particular date time range in the control. Its rich feature set includes, minor and major scale auto calculation, interactive range selection, visualizing the data using built-in chart, tooltip, smart labels and much more.

![rangeNavigator](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/rangeNavigator/gettingstarted/finalView.png)

|  |
| --- |
|  |


#<a id="Schedule"></a>Schedule

The Schedule control for Xamarin.Forms lets you to manage appointments with intuitive user interface similar to native calendar. Its rich feature set includes functionalities like data binding, Navigation, Date Restrictions.

![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/intro.png)

**Views**

It has four types of built-in views to display the appointments based on requirement.

![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/dayview.png) 
![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/weekview.png) 
![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/workweekview.png) 
![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/monthview.png) 

**Flexible Data Binding**

Ability to bind the custom appointments by mapping its properties instead of converting into schedule defined appointment type.

**Date Navigation**

Has ability to block and disable the interaction with specific time slots.

**Recurrence Appointments**

It has support to create, view and edit recurrence appointments.

![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/recurrence.png) 

**Block Time Slot**

Has ability to block the interaction with specific time slots.

![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/nonaccessibleblock.png) 

**Navigation**

Has ability to prevent date navigation with minimum and maximum value.

**Localization**

Every static text of schedule can be localized to desired language.

![schedule](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/schedule/localization.png) 

|  |
| --- |
|  |

#<a id="CircularGauge"></a>CircularGauge

The CircularGauge control for Xamarin.Forms lets you visualize numeric values over a circular scale. The appearance of the gauge can be fully customized to seamlessly integrate with your applications.

**Range Indicators**

Range indicators help quickly visualize the range within which a value falls on a scale. This functionality is very useful when needing to quickly determine if a value has crossed a certain threshold.

![CircularGauge](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/gauge/ft-radial-indicator-1.png) 

**Customizable Frames**

The CircularGauge control can be rendered within circular, semi-circular, and quadrant frames so it fits within the available space.

![CircularGauge](http://www.syncfusion.com//content/en-US/Products/Images/Xamarin/gauge/ft-customizable-frame-1.png)

**Needle Pointer**

The current value can be indicated by using a fully customizable pointer.

![CircularGauge](http://www.syncfusion.com//content/en-US/Products/Images/Xamarin/gauge/ft-needle-pointer-1.png)  

**Range Pointer**

The range pointer can be alternatively used in place of the needle pointer

![CircularGauge](http://www.syncfusion.com//content/en-US/Products/Images/Xamarin/gauge/ft-range-pointer-1.png)

|  |
| --- |
|  |

#<a id="DigitalGauge"></a>DigitalGauge

The Digital Gauge control for Android lets you visualize alpha and numeric values over a Digital Gauge frame. Digital gauge is used to display a range of values that uses character in combination with numbers.

![DigitalGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/digitalgauge/digitalgauge.png)

**Appearance**

The digital gauge supports many customizations such as foreground and background colors.

![DigitalGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/digitalgauge/appearance.png)

**Display Type**
The digital gauge can display numbers as well as alphabetic characters in its output. Special characters support can also be displayed.

![DigitalGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/digitalgauge/displaytype.png)

**Character Type**
Digital gauge supports 4 types of character types; seven-segment, fourteen-segment, sixteen-segment and eight by eight dot matrix.

![DigitalGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/digitalgauge/charactertype.png)

**Customizations**
The segments of a digital gauge can be customized in terms of segment width, segment height, spacing between segments, and color.

|  |
| --- |
|  |

#<a id="LinearGauge"></a>LinearGauge

The LinearGauge control for Xamarin.Forms lets you visualize numeric values over a rectangular scale. The appearance of the gauge can be fully customized to seamlessly integrate with your applications.

![LinearGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/lineargauge/lineargauge.png)

**Orientation**

Linear gauges can be positioned either in a vertical or horizontal orientation, according to the user's required scenarios.

![LinearGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/lineargauge/orientation.png)

**Appearance**
The appearance of each elements of a linear gauge such as its state indicators, pointers, scale intervals, pointer positions, label positions, tick positions, and much more is easily customizable.

**Range Indicators**
Essential Gauge supports range indicators which can be used to highlight each specific ranges within a gauge scale with different colors. The user can specify their required start and end values for each range indicators within the gauge. They can also be located at different positions — such as cross (across the scale), inside (below the scale), and outside (above the scale).

![LinearGauge](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/lineargauge/range.png)

|  |
| --- |
|  |

#<a id="TreeMap"></a>TreeMap

The TreeMap control for Xamarin.Forms provides a simple but effective way to visualize flat or hierarchical data as clustered rectangles with proportions determined by data values.

**High Performance**

The TreeMap control is optimized to visualize large amounts of flat or hierarchical data.

![TreeMap](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/tree-map/large-data.png)

**Grouping**

Data can be grouped to provide a top-level view.

![TreeMap](http://www.syncfusion.com/content/en-us/products/images/Xamarin/tree-map/grouping.png)

**Rich Interactivity**

Readability of the data can be greatly enhanced using interactive legends and labels.

![TreeMap](http://www.syncfusion.com/content/en-us/products/images/Xamarin/tree-map/tree-map-elements.png)

**Layout Options**

Visualize data using one of the available layout algorithms, such as **Squarified** , **SliceAndDiceAuto** , **SliceAndDiceHorizontal** , or **SliceAndDiceVertical** to depict the relative weight of hierarchical data relationships at more than one level.

![TreeMap](http://www.syncfusion.com/content/en-us/products/images/Xamarin/tree-map/ft-squarified-1.png)

![TreeMap](http://www.syncfusion.com/content/en-us/products/images/Xamarin/tree-map/ft-sliceanddiceauto-1.png)

![TreeMap](http://www.syncfusion.com/content/en-us/products/images/Xamarin/tree-map/ft-sliceanddicehorizontal-1.png)

![TreeMap](http://www.syncfusion.com/content/en-us/products/images/Xamarin/tree-map/ft-sliceanddicevertical-1.png)

|  |
| --- |
|  |

#<a id="Maps"></a>Maps

Maps control helps to visualize statistical data of geographical area on globe as map. 

![Maps](http://www.syncfusion.com/content/en-us/products/images/Xamarin/maps/maps.png)

**ESRI Shape files** 

Render ESRI Shape files to collect geometric location information and associated attributes. The Shape files spatially describe a map’s geometries as points, polylines, and polygons. 
 
![Maps](http://www.syncfusion.com/content/en-us/products/images/Xamarin/maps/shapes.png)         

 **Intuitive Markers** 
 
Provides customizable markers to showcase your data at specific mark points based on latitude and longitude position.      

![Maps](http://www.syncfusion.com/content/en-us/products/images/Xamarin/maps/markers.png)         

 **Visualize Data with Bubbles** 

Provides bubbles to visualize detailed map data represented in variable sizes based on values.

![Maps](http://www.syncfusion.com/content/en-us/products/images/Xamarin/maps/colormapping.png)         

**Legends** 

Provides legends to showcase valuable information for interpreting the map.

![Maps](http://www.syncfusion.com/content/en-us/products/images/Xamarin/maps/legends.png)

|  |
| --- |
|  |

#<a id="Barcode"></a>Barcode

Essential Barcode enables rendering of barcodes in Android, iOS and Windows Phone.It Supports both 1D and 2D barcodes

**Barcode Types**

Barcode supports Code39, Code39Extended, Code93, Code93Extended, Code11, Code32, Codabar, Code128A, Code128B, Code128C in 1D Barcode and Data Matrix and QR Codes in 2D barcode.

**Code39**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code39.png)

**Code39Extended**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code39Extended.png)

**Code93**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code93.png)

**Code93Extended**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code93Extended.png)

**Code11**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code11.png)

**Code32**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code32.png)

**Codabar**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Codabar.png)

**Code128A**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code128A.png)

**Code128B**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code128B.png)

**Code128C**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Code128C.png)

**QR_code**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/QR_code.png)

**data_matrix**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/data_matrix.png)

**Text_custom**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Text_custom.png)

**Bar_custom**

![Barcode](http://www.syncfusion.com/content/en-us/products/images/Xamarin/barcode/Bar_custom.png)

|  |
| --- |
|  |

#<a id="XlsIO"></a>XlsIO

Essential XlsIO for Xamarin is a .NET PCL library that can be used to create and modify Microsoft Excel documents from within Xamarin.iOS, Xamarin.Android and Xamarin.Forms applications.

**Supported Features**

- Charts for data visualization
- Conditional Formatting
- Data Validation
- Tables
- Importing XML data
- Importing Business Objects
- Formulas
- Template Marker
- Auto-Shapes
- Cells Formatting
- Cell Grouping
- Data Filtering
- Data Sorting
- Find Data
- Comments
- HTML Conversion
- Named Ranges
- Number Formats
- Page settings
- Page breaks
- Header and footer images
- R1C1 Reference Mode
- Re-calculation
- R1C1 Formulas
- Dis-contiguous Named Ranges
- Hyperlinks
- Freeze panes
- Sheet Tab color RGB
- Hide rows and columns

![XlsIO](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/XlsIO/excel_invoice.png)

|  |
| --- |
|  |

#<a id="DocIO"></a>DocIO

Essential DocIO for Xamarin is a .NET PCL library that can be used to read and write Microsoft Word documents from within Xamarin.iOS, Xamarin.Android and Xamarin.Forms applications.

**Features**

Here is a quick summary of the features available in Essential DocIO

- Create new Word documents.
- Modify existing Microsoft Word documents.
- Format text, tables using built-in and custom styles.
- Insert bullets and numbering.
- Insert, edit, and remove fields, form fields, hyperlinks, endnotes, footnotes, comments, Header footers.
- Insert and extract images, OLE objects.
- Insert line breaks, page breaks, column breaks and section breaks.
- Find and Replace text with its original formatting.
- Insert Bookmarks and navigate corresponding bookmarks to insert, replace, and delete content.
- Advanced Mail Merge support with different data sources.
- Clone multiple documents and merge into a single document.
- Read and write Built-In and Custom Document Properties.
- Define page setup settings and background. 
- Create or edit Word 97-2003, 2007, 2010, and 2013 documents



![DocIO](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/DocIO/word_invoice.png)

|  |
| --- |
|  |

#<a id="PDF"></a>PDF

Essential PDF for Xamarin is a .NET PCL library that can be used to create and modify Adobe PDF documents from within Xamarin.iOS, Xamarin.Android and Xamarin.Forms applications.

All of the elements in a typical PDF file like the text, formatting, images and tables are accessible through a comprehensive set of API's. This makes it possible to easily create richly formatted PDF documents as well as modify existing ones.

**Features:**

**Document level features:**

- Create and load PDF documents files and streams
- Save PDF files to disk and Streams
- Document information
- Document viewer preference
- Document file attachments
- Document level java scripts and actions
- Document outline
- Add and remove Pdf pages
- Import page form existing document
- Document merging 
- Booklet
- Stamp
- Page orientation
- Page sizes
- Headers and Footers
- Actions

**Text**

- Drawing Text
- Text formatting
- Pagination

**Graphics**

- Pen and brush for stroking operations
- Graphics primitives: lines, ellipses, rectangles, arcs, pie, Bezier curves, paths.
- Layers
- Patterns
- Drawing of external page content
- Color spaces
- Barcode

**Forms**

- Create, load and save PDF forms
- Add, edit, remove and rename form fields
- Supporting text box fields, combo box fields, list box fields, push button fields, radio button fields
- Flatten form fields
- Enumerating the form fields
- Form actions

**Fonts**

- Standard Fonts

**Images**

- Jpeg image support

**Tables:**

- Cell/Row/Column formatting
- Header
- Pagination
- Borders
- Row span and column span
- Nested
- Cell Padding and spacing

**Page Level Operations**

- Headers and Footers
- Page Label
- Automatic fields

**Pdf Annotations**

- Add, edit and remove pdf annotations
- Custom appearance for annotations

**Supported annotations**

- Free Text annotation
- Rubber stamp annotations
- File attachment annotation
- Link annotation
- Line annotation
- Ink annotations
- Text markup annotations
- sound annotations
- 3D-Annotations.

**Barcode**

- Add the barcode into the PDF document

**Supported barcodes:**

- QR barcode
- Data matrix barcode
- Code39
- Code39ext
- Code 11
- Coda bar
- Code32
- Code93
- Code93 extended
- Code128 A
- Code128 B
- Code128 C

![Pdf](http://www.syncfusion.com/Content/en-US/products/Images/Xamarin/Pdf/pdf_invoice.png)

|  |
| --- |
|  |

#<a id="BusyIndicator"></a>BusyIndicator

The BusyIndicator has 10 built in animations.

![BusyIndicator](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/busyindicator/busyindicator.png)

**Custom Message**

The Title property can be used to customize the label for each animation.

![BusyIndicator](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/busyindicator/title.png)

|  |
| --- |
|  |

#<a id="RangeSlider"></a>RangeSlider

RangeSlider allows the user to select the range of values. The range can be adjusted by moving the thumb control along a track.

![RangeSlider](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rangeslider/rangeslider.png)

**Orientation**

RangeSlider can be horizontal or vertical.

![RangeSlider](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rangeslider/orientation.png)

**Slider View**

RangeSlider can be used as a simple slider.

![RangeSlider](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rangeslider/slider.png)

**Customization**

Ability to customize the appearance of Tick and Label using placement options.

![RangeSlider](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rangeslider/customization.png)

|  |
| --- |
|  |

#<a id="AutoComplete"></a>AutoComplete

The AutoComplete control simplifies data input by providing end users with possible matches as soon as they start typing.

![AutoComplete](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/autocomplete/autocomplete.png)

**AutoCompleteMode**

The AutoCompleteMode property can be used to display the filtered suggestions like Suggest, Append and SuggestAppend.

![AutoComplete](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/autocomplete/autocompletemode.png)

**Watermark**

The WaterMark will prompt the user with some information, when it is not in focus and contains an empty string.

![AutoComplete](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/autocomplete/watermark.png)

|  |
| --- |
|  |

#<a id="NumericTextBox"></a>NumericTextBox

Numeric textbox restricts the input to numeric values. The control respects the UI culture and can be configured to display different formats like currency format, scientific format, etc.

![NumericTextBox](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/numerictextbox/numerictextbox.png)

**Culture**

The Culture property can be used to represent the values based on the provided culture.

![NumericTextBox](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/numerictextbox/culture.png)

|  |
| --- |
|  |

#<a id="Calendar"></a>Calendar

Calendar control provides an elegant UI to visualize and selecting dates in month view.

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/calendar.png)

**Navigation**

Built-in year view made easy month navigation.

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/navigation.png)

**Selection**

Options to perform the single and multiple dates selection.

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/selection.png)

**Inline Events**

End users can show their appointment details using inline events represented in expanded view of date cell.

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/inline.png)

**Date Constraints**

Efficient date restrictions functionality to preventing selection with certain dates.

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/blackoutdays.png)

**Globalization**

It has built-in complete globalization support to represent the Calendar to its specific culture.

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/monthculture.png)

![Calendar](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/calendar/yearculture.png)

|  |
| --- |
|  |

#<a id="Rating"></a>Rating

Rating control has a group of stars to indicate the rating with flexible precisions.

![Rating](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rating/rating.png)

**Flexible Precision**

Provides flexible precision to handle full, half or exact values of rating.

![Rating](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rating/precision.png)

**Customization**

Look and feel can be customized to fit your application.

![Rating](http://www.syncfusion.com/content/en-US/Products/Images/Xamarin/rating/customization.png)

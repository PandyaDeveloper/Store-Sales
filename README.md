# Store-Sales
Machine Learning Project


## Introduction


## File Descriptions and Data Field Information
<dl>
  <dt><h3>train.csv</h3></dt>
    <li>The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.</li>
    <li>store_nbr identifies the store at which the products are sold.</li>
    <li>family identifies the type of product sold.</li>
  <li>sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).</li>
  <li>onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.</li>
  <dt><h3>test.csv</h3></dt>
  <li>The test data, having the same features as the training data. You will predict the target sales for the dates in this file.</li>
  <li>The dates in the test data are for the 15 days after the last date in the training data.</li>
  <dt><h3>sample_submission.csv</h3></dt>
  <li>A sample submission file in the correct format.</li>
  <dt><h3>stores.csv</h3></dt>
  <li>Store metadata, including city, state, type, and cluster.</li>
  <li>cluster is a grouping of similar stores.</li>
  <dt><h3>oil.csv</h3></dt>
  <li>Daily oil price. Includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices.)</li>
  <dt><h3>holidays_events.csv</h3></dt>
  <li>Holidays and Events, with metadata</li>
  <li>NOTE: Pay special attention to the transferred column. A holiday that is transferred officially falls on that calendar day, but was moved to another date by the government. A transferred day is more like a normal day than a holiday. To find the day that it was actually celebrated, look for the corresponding row where type is Transfer. For example, the holiday Independencia de Guayaquil was transferred from 2012-10-09 to 2012-10-12, which means it was celebrated on 2012-10-12. Days that are type Bridge are extra days that are added to a holiday (e.g., to extend the break across a long weekend). These are frequently made up by the type Work Day which is a day not normally scheduled for work (e.g., Saturday) that is meant to payback the Bridge.</li>
  <li>Additional holidays are days added a regular calendar holiday, for example, as typically happens around Christmas (making Christmas Eve a holiday).</li>
</dl>

### Additional Notes
<ul>
  <li>Wages in the public sector are paid every two weeks on the 15 th and on the last day of the month. Supermarket sales could be affected by this.</li>
  <li>A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.</li>
</ul>

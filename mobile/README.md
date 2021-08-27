# Finblox: Currency chart

For this project, you will be building a Flutter application that displays a currency chart. The application will also allow the user to change the periods of the chart and see the current price on the chart view by long-tapping it.

You may work using all the tools and reference materials that you usually use. You may use any 3rd party libraries, but please be ready to justify their usage and explain their inner workings. When you're done, zip up your project directory and share it with us.

Please don't spend more than 3 hours on this project.

## Requirements

* The application will display a bitcoin currency chart
* It will allow the user to change the chart periods, the available periods:
    * 1 week
    * 1 month
    * 6 months
* By tapping on a period that chart needs to show the data for:
    * The chart shows the progress indicator (we assume that the application would go and fetch the data from the server)
    * The chart loads the data from the data source (you should use some mock data for this cause, it does not matter what the data is, let's assume it is correct)
    * Once the data is loaded, the chart shows it to the user
* By long-tapping on the chart view, the users should see the price with the date he is currently at (You can decide how it would look like)
* You can make your own assumptions and compromises as long as you understand the trade-offs and will be able to articulate those in documentation

## Expectations

We would like to see:
* Idiomatic code and ability to explain code without documenting each line
* Use of any architecture/state management approach you're familiar with. Using BLOC would be a plus.
* Tests or at least testable code
* Reasonable level of documentation

## Design Specification

The design is just for reference.

<img src="https://github.com/finblox/public/raw/main/mobile/assets/image_chart.png">

## Questions

If you have any questions, please reach us at engineering@finbloxapp.com
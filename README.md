# Binomial Distribution Calculator

This is a web application that calculates and displays the binomial distribution for a given set of parameters. The user can enter the number of trials (n) and the probability of success (p) in each trial, and the application will calculate and display the probability of each possible number of successes (x).

## Tools and Technologies Used

- HTML, CSS, and JavaScript for the front-end
- Bootstrap for the layout and styling
- Chart.js for creating charts
- PHP for server-side processing (optional)

## How to Use

    1. Enter the number of trials (n) and the probability of success (p) in each trial in the form provided.
    2. Click the "Calculate binomial distribution" button to trigger the calculation.
    3. The probability of each possible number of successes (x) will be displayed in a bar chart.

## Customization

You can customize the appearance of the chart by modifying the values of the backgroundColor, borderColor, and borderWidth properties in the datasets array, and the ticks properties in the yAxes array in the JavaScript code.

```
datasets: [{
  label: 'Probability',
  data: distribution.map(function(d) { return d.probability; }),
  backgroundColor: 'rgba(255, 99, 132, 0.2)',
  borderColor: 'rgba(255, 99, 132, 1)',
  borderWidth: 1
}]

options: {
  scales: {
    yAxes: [{
      ticks: {
        beginAtZero: true
      }
    }]
  }
}
```

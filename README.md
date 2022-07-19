# Custom UFO Weboage

## Project Overview
The purpose of this project is to build a UFO webage for Dana. The webge is built with JavaScrpt,HTML and CSS.

## Resources and Software

- HTML
- Javascript
- D3.JS
- CSS

## Results

Webpage was sucessful built with general infomation and filter. All the data.js information is able to be found on the webpage with correct format and table will be updated and return results by using search fields.

![image](https://user-images.githubusercontent.com/104603177/179436122-5649eb03-fee4-4366-ac26-e6c8b89cafd1.png)

## Summary

Based on the analysis report above, Surf shop in Oahu will have less customers in December than in June due to the slight decrease in average daily temperature.

It is important to have the most relevant results when conducting analysis on a potential business venture. We are using two addtional queries to perform to gather more weather date for June and December which is most representive data during the selected year.
Dec_results = []
Dec_results = session.query(Measurement.date, Measurement.tobs).filter(extract('month', Measurement.date) == 6).all()
Dec_results = []
Dec_results = session.query(Measurement.date, Measurement.tobs).filter(extract('month', Measurement.date) == 12).all()










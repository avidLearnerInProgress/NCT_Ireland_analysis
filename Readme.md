# NCT Analysis

## About

NCT stands for National Car Test. The NCT is a compulsory vehicle inspection programme in Ireland. The primary aim of this programme which falls under the EU Directive 2014/45, is to improve road safety and enhance environmental protection by reducing harmful vehicles emissions in Ireland.

## Description

The Road Safety Authority (RSA) has provided the following information relating to vehicle makes and models tested by the National Car Testing Service in 2016. 

The main fields, for example, are summarised as follows:
- "VehicleMake" and "VehicleModel" - these fields detail the vehicles make and model
- "YearOfBirth" - this field details the vehicles year.
- "Total" - this field relates to the total NCT's completed by each car model.
- "PASS" and "PASS%" - these fields relate to the total NCT's that by each car model that were successful.
- "FAIL" and "FAIL%" - these fields relate to the total NCT's that by each car model that were unsuccessful.
- The remaining fields were the different items that the vehicles failed on.
Overall this is a broad dataset with a variety of information about the Vehicles which have been tested by the NCT.

The data has been preprocessed and field names are changed to make it more meaningful.
The aim of this project was to gain an insight into this data and producing three effective visualisations using Vega-Lite. More information can be found about Vega-Lite [here](https://vega.github.io/vega-lite/)

## Following are the visualisations implemented -

### **Mean Pass % vs NCT Failures due to Vehicle and Safety Equipments** [code](/code/vega_spec/Vis1.json.vg)

<p align="center">
<img src="/output/vis1.png" height = 500></img>
</p>

------

### **Top vehicle manufacturer between 2007-2010** [code](/code/vega_spec/Vis2.json.vg)

<p align="center">
<img src="/output/vis2.png" height = 500></img>
</p>

------

### **Impact of fail items on different models of 'Volkswagen' car manufacturer** [code](/code/vega_spec/Vis3.json.vg)

<p align="center">
<img src="/output/vis3.png" height = "auto"></img>
</p>
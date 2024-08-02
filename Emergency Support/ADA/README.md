# Automated Damage Assessment

## Scope and Objective
### Purpose
The Automated Damage Assessment tool (ADA) is a deep learning model that identifies damaged buildings in satellite images after a disaster has happened.
Automating this assessment makes it faster and far less dependent on human effort, therefore enabling 510 to quickly deliver the information that is needed. 
The assessment time decreases from weeks to hours, which makes a difference in the speed of operations and, ultimately, on the number of lives that can be saved.

### Target Audience
Emergency Operators in areas affected by natural and/or man-made disasters.

### End Product
The ADA tool produces a damage map in PDF format that highlights the locations of damaged buildings. Additionally, upon request, damage predictions in GeoJson format can be shared. 

## Service Access and Availability
### Prerequisites to Deploy
Before deploying ADA, it is essential to ensure access to a sufficient number of satellite images that meet specific requirements. These requirements include image resolution, spectral capabilities, 
and freedom from cloud cover (requirements specified below).
  
### Technical Requirements
Technical requirements may vary depending on deployment environments and specific use cases. These requirements typically involve computational resources for running the deep learning model and accessing satellite image data.
  
### Service Level Agreement
No formal Service Level Agreement (SLA) is required for deploying ADA

## Data Quality

To effectively perform damage assessment, ADA requires satellite images meeting the following criteria:

- Optical (RGB), or multi-spectral with optical
- High-resolution (<0.6 m/pixel)
- Cloud-free
- With visible building damage

Common sources of high-resolution optical satellite images are:
- [Maxar](https://www.maxar.com/open-data)
- [Airbus](https://www.airbus.com/en/space/earth-observation/satellite-imagery)
- [Planet](https://www.planet.com/products/planet-imagery/)
  
### Data Responsibility/Policy
Before handover, ADA results always undergo a manual validation process, involving triangulation and manual verification, to ensure accuracy. 
Additionally,  sharing of generated data, such as damage maps, with external parties might be restricted by *.....*

## Limitations and Risks
ADA is limited to detecting damage to buildings visible from an aerial perspective. It is designed to provide an overview of damaged buildings within a specific area,
rather than conducting detailed assessments of individual structures. *Any risks?*

## More Info

### Technical Documentation
For detailed technical documentation and instructions on deploying the ADA, users can refer to its GitHub repository: [rodekruis/ada-collection](https://github.com/rodekruis/ada-collection).

### Contact Info
For a demo, please each out to bselvan@redcross.nl

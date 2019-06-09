# PIMS-CloudPBX-Data-Analysis
Analysis on CloudPBX's data. The data that was worked on was kindly provided by [CloudPBX](http://www.cloudpbx.ca/ "CloudPBX's Home Page"), they are a PBX provider who service both independent customers and businesses. They were interested in investigating how they could better improve their services so they took part in the [BCData Science Workshop](
http://workshop.bcdata.ca/2018/#about "BCData Home Page") which is a week long workshop where participants will have the opportunity to work with big data, learn data analysis and so much more in a team setting: I highly recommend taking part in future events if you are given the chance.

More information can be found [here.](http://workshop.bcdata.ca/2018/post/5-cloudpbx-project/)

This repo is a culmination of the work I completed during this workshop. I would definitely have to note that this is product of the collaboration between all my team members during the event ([stefanhannie](https://github.com/stefanhannie),[imachuca24](https://github.com/imachuca24),[mlardadji](https://github.com/mlardadji),[eclam](https://github.com/eclam),[jackiexu007](https://github.com/jackiexu007) and [clm222](https://github.com/clm222) and with the expertise of our supervisors ([mattfung](https://github.com/mattfung) and [grahamsnz](https://github.com/gragamsnz)). There is some work that is absent here, but if you are so inclined feel free to look at the [master repo](https://github.com/mattfung/pims-bcdata18-cloudpbx "Master Mess").

### Tools & Libraries Used:
- Jupyter notebooks hosted by BCData
- Python 3.6
- Dask 
- Pandas
- Numpy
- Matplotlib
- Geolite
- GeoIP2
- scipy

### Tools & Libraries that require further implementation towards this project:
- xtensor
- Boost.python

# File explanation: 

- File Dump: there are some examples for coordinates and html pages used for the final mapping.
- Final Mapping: holds all the required files for the animation. 
- Smaller Notebooks: holds notebooks on adding information to the data.
- Network Mapping: Data necessary to plot CouldPBX’s network. 
- CloudPBX Workshop presentation: is the final presentation that the group published. 
- Deep Dive into MOS: shows how MOS works and how it the data relates to it. 
- MOS Qualfun Analysis: shows how Qualfun is calculated and how it highlights calls on the data.
- Call quality: analyses the quality of calls in the network. 
- Loading 7 million entries shows how to load large datasets. 


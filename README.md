# UFO Searchable Table Project

## Overview of Project


### Purpose

In this project, we used a data set with information regarding different UFO sightings from the year 2010. Our goal was to create a table that was searchable by four different criteria: date, city, state, and country. This was all done to make this information easily searchable and readable for skeptics and believers alike so they all the information was in one easily accessible website.

# Analysis


## Results
### Step-By-Step Walkthrough
- The website was designed with ease-of-use in mind. Because of that, we have all the information displayed from the start as well as example searches so the end-user knows how to filter the searches with their input. 

<p align="center">
<img width="960" height="540" src="https://user-images.githubusercontent.com/85508764/131146496-e96cf3d4-8f77-4b9f-9091-169b10b0ce87.png">
</p>

- From there users can simply type in the specifics of what they want to find. For instance, if a user lived in Fort Worth, Texas, they could simply type in Houston and the state code and the table would automatically filter the results to only get sightings from Fort Worth.

<p align="center">
<img width="960" height="540" src="https://user-images.githubusercontent.com/85508764/131146849-a40a86d5-6beb-4c65-8816-14bda969d8c4.png">
</p>

- From there, the users simply have to change whatever is in the filter fields and the table will once again update automatically. Below, the fields were changed to remove fort worth from the city field and updated to search for all Texas sightings.

<p align="center">
<img width="960" height="540" src="https://user-images.githubusercontent.com/85508764/131146902-096ef878-919f-4517-a76d-acd31dd3514b.png">
</p>





# Summary

There are a couple of fields missing that users might potentially be interested in filtering by. Most likely, they would like to be able to search for the duration of the UFO sighting to see if their experiences match up with other people who may have potentially seen similar sightings. This is a relatively easy fix however, by adding another list item, we could allow for users to search for specific durations of sightings. Note that this would require the data set to be homogenized to a similar format to make it easier for users to search for specific times. 

In addition to adding new fields for searching, using regex to clean up the data where the data copied over strangely is also recommended. (ie. Three red lights over the San Diego area - IT&#39S A HOAX YET AGAIN&#33&#33). Also, CSS stylings could be used to make using the site a more polished experience. For example, users currently need to scroll down the page a little bit to see all the fields available for filtering.

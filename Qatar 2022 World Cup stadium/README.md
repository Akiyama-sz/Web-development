# worldcup2022stadiums

## Instructions to add events and images to stadium pages

1. Add the event image file to the following folder: assets/images/

2. Find the following code on the desired stadium page, and add the code from step 3 above the line:
```
<!--  --------------------------------------------------------------------------------------------------------  -->
<!-- Add the section of the code above this line, as instructed on the Readme.md file -->
<!--  --------------------------------------------------------------------------------------------------------  -->
```

3. Add the following code:
```
<div class="eventList">
    <img src="../assets/images/<< image file name >>" alt="<< Image description >>">
    <div class="event-info">
        <div class="flex flex-row">
            <span class="event-title w-80"> << Event Title >> </span>
            <!--  Delete the line below if there are no external event webpage  -->
            <a class="insta-link" href="<< Link to Event Webpage >>"><i class='fa fa-globe' title = "External Webpage"></i></a>
            <!--  Delete the line below if there are no event instagram page  -->
            <a class="insta-link" href="<< Link to Event Instagram Page >>"><i class='fa fa-instagram' title = "Instagram"></i></a>
        </div>
        <p class="flex flex-row">
            <strong class="w-80"> << Event Date >> </strong>
            <span class="w-20"> << Event Days >> </span>
        </p>
        <p> << Event Description >> </p>
    </div>
</div>
```

**Note:**
Replace the following texts with appropriate event informmation:
- **<< image file name >>**
- **<< Image description >>**
- **<< Event Title >>**
- **<< Link to Event Webpage >>**
- **<< Link to Event Instagramm Page >>**
- **<< Event Date >>**
- **<< Event Days >>**
- **<< Event Description >>**


## Instructions to add events and images to event pages


## Instructions to add events and images to why visit pages
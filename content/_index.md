+++
title = "UCL Economic Geography Network Zola Theme"
+++

# Intro

Established in February 2023, the UCL Economic Geography Network brings together academics and PhD students across UCL researching broadly in the field of Economic Geography or other related disciplines bringing economics into conversation with the urban, and geography.

## On our Network

* Our cross-disciplinary network includes urban economists, human, urban and feminist geographers, planners, architects, urban sociologists, applied mathematicians, spatial data scientists and statistical physicists.
* The network is hosting a series of monthly internal seminars - please check the schedule below for info on our speakers and seminar venues.
* The informal seminars include presentations of recently completed work, work in progress and emerging research ideas.

{{ new_block() }}

### UCL webpage

Further details on our [UCL webpage]([https://github.com/aterenin/academic-workshop](https://www.ucl.ac.uk/bartlett/events/2026/mar/economic-geography-network-seminar-series)) !

{{ new_block() }}

# List of Speakers

{{ grid(
    text = [
        ["Dr Carolin Hulke","London School of Economics (LSE)"], 
        ["Dr Konstantinos Melachroinos","Queen Mary University of London (QMUL)"],
        ["TBC","University College London (UCL)"],
    ],
    urls = [
        "https://www.lse.ac.uk/people/carolin-hulke",
        "https://www.qmul.ac.uk/geog/staff/academicstaff/profiles/melachroinosk.html",
        "",
    ],
    images = [
        "placeholder.svg",
        "placeholder.svg",
        "placeholder.svg",
    ],
    narrow = true) }}



{{ new_block() }}

# Past Speakers

{{ grid(
    text = [
        ["Dr Laurie Parsons","Royal Holloway University of London (RHUL)"], 
        ["Dr Siddharth Menon","London School of Economics (LSE)"],
        ["Dr Zahratu Shabrina","King's College London (KCL)"],
    ],
    urls = [
        "https://pure.royalholloway.ac.uk/en/persons/laurie-parsons/",
        "https://www.lse.ac.uk/people/siddharth-menon",
        "https://www.kcl.ac.uk/people/zahratu-shabrina",
    ],
    images = [
        "placeholder.svg",
        "placeholder.svg",
        "placeholder.svg",
    ],
    narrow = true) }}



{{ new_block() }}

# List of Organizers

{{ grid(
    text = [
        "Organizer A",
        "Organizer B",
    ],
    image_dir = "organizers") }}


{{ new_block() }}



# Schedule

| Time             | Event            |
| ---------------- | ---------------- |
| 12:00pm - 1:00pm | Introduction and Opening Remarks: Speaker Name A     |
| 1:00pm - 2:00pm  | Speaker A        |
| 2:00pm - 3:00pm  | Speaker B        |
| 3:00pm - 4:00pm  | Discussion Panel |



{{ new_block() }}



# Accepted Papers

{{ table(
    data = "papers.csv", 
    columns = ["Title","Authors"],
    button_names = ["paper","poster"], 
    button_data_columns = [3,4], 
    button_output_columns = [1,1]) }}



{{ new_block() }}



# Upcoming Seminar

{{ highlights(section_name = "seminars") }}



{{ new_block() }}



# List of Seminars

{{ list(section_name = "seminars") }}

{{ button(name = "All Seminars", url = "seminars")}}

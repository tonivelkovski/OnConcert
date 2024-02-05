# OnConcert
This project was done as an assignment for the university course Software Analysis and Design in collaboration with Span (JCC course).

# Functionalities

| **Role**           | **Functionality**                                     | **Description**                                                                                 |
|--------------------|-------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Organizer          | Organizer/venue profile                               | Organizers and venues can create their profiles with basic information, contacts, and event histories. |
|                    | Description of venue, event, and concert times        | Organizers provide detailed descriptions of the concert venue, event information, and event dates. |
|                    | Selection of registered groups                        | Organizers review and select groups/musicians that have applied to perform at the concert.   |
|                    | Group evaluation                                      | Organizers have the ability to rate and evaluate the registered groups to choose the best ones. |
| Group/Musician     | Group/musician profile                                | Groups and musicians can create their profiles with biographical information and details about their work (albums, singles, concerts, etc.). |
|                    | Finding events and applying                           | Groups can browse available concerts and apply to perform.                                      |
|                    | Event application                                     | Groups submit their performance applications for specific concerts.                              |
|                    | Chat/"wall" for communication (shared with all groups and organizers) | Groups can communicate with other performers and organizers via a shared chat wall to coordinate performance details. |
|                    | Venue evaluation                                      | Groups can rate the venue after their performance to provide feedback.                           |
| Visitor            | Google login                                          | Visitors can sign in with their Google accounts to participate in rating groups and venues. |
|                    | Rating groups and venues                              | Visitors can rate performers and concert venues after the concert and share their impressions and reviews. |

# Documentation

ER diagram can be accessed via [link](Documentation/ERA.svg).

API architecture can be accessed via [link](Documentation/Architecture.png).


# Running the MS SQL Server

### Required tools

* [Docker Engine](https://docs.docker.com/get-docker/) (v. 24)
* [Docker Compose](https://docs.docker.com/get-docker/) (v. 2)

Or you can download [Docker Desktop](https://docs.docker.com/desktop/), which includes both the Docker Engine and Compose tool.

### Running the defined networks, services, and volumes

From the root directory, run the following command:
```bash
docker-compose up [--detach]
```

### Closing the defined networks, services, and volumes

From the root directory, run the following command:
```bash
docker-compose down [--detach]
```



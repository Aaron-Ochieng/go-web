# Groupie-Tracker-Geolocalization

Groupie Tracker Geolocalization is a web application designed to map the concert locations of various artists and bands, utilizing geographic coordinates to visually display these locations on a map.

## API Overview

The provided API consists of four main parts:

1. **Artists**: Contains information about bands and artists, including their names, images, the year they began their activity, the date of their first album, and the members.
2. **Locations**: Lists the last and/or upcoming concert locations.
3. **Dates**: Provides the last and/or upcoming concert dates.
4. **Relation**: Links the artists, dates, and locations.

## Features

- Data Visualization: Displaying concert locations using markers on a map.
- Geocoding: Converting addresses into geographic coordinates to place markers for concert locations.
- Error Handling: Implementing robust error handling for website interactions.
- Client-Server Communication: Request-response model to fetch artist and concert data.

## Implementation Overview

The HTML implementation includes:

- Artist Details Section: Displays the artist's image, name, first album, and band members.
- Tour Dates and Locations: Lists the upcoming tour dates and corresponding locations for the artist.
- Map Integration: Utilizes the Leaflet library to display a map and place markers for concert locations.

## Project Requirements

Ensure that you have `go` installed on your machine before running the project.

Also ensure that you have `git` installed on your machine 

## Features

- **Data Visualization**: Displaying band information using various formats such as blocks, cards, tables, lists, pages, and graphics.
- **Client-Server Communication**: Implement a feature that triggers an action on the client side, which communicates with the server to receive information (request-response model).
- **Event Creation and Display**: Create and visualize events/actions that respond to client actions, time, or other factors.

## Learning Objectives

This project will help you learn about:

- Manipulation, display and storage of data
- HTML
- Events creation and display
- JSON files and format

## Usage

To run the project, follow these steps:

1. Clone the repository.
   
   ```bash
   git clone https://learn.zone01kisumu.ke/git/bshisia/groupie-tracker-search-bar
   ```

2. Navigate to the project directory.
   
   ```bash
   cd groupie-tracker-search-bar
   ```

3. Run the server using the command:
   
   ```sh
   go run .
   ```

4. Open your browser and go to `http://localhost:8000` to view the website and interact with it.
   
   **To view locations and concert dates of the individual artists, click on the artists card(any artist) to view more about the artist.**

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://learn.zone01kisumu.ke/git/aaochieng>
            <img src=https://learn.zone01kisumu.ke/git/avatars/8a1b24358854eb12998a07c269542193?size=870 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Aaron/>
            <br />
            <sub style="font-size:14px"><b>Aoron Ochieng</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://learn.zone01kisumu.ke/git/moonyango>
            <img src=https://learn.zone01kisumu.ke/git/avatars/8f9cf111e69139c3033e3b9f679e91ce?size=870 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Emmanuel/>
            <br />
            <sub style="font-size:14px"><b>Moses Onyango</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://learn.zone01kisumu.ke/git/bshisia>
            <img src=https://learn.zone01kisumu.ke/git/avatars/e6b283b461701c3a0bde65d94393f768?size=870 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Abraham/>
            <br />
            <sub style="font-size:14px"><b>Brian Shisia</b></sub>
        </a>
    </td>
</tr>
</table>

---

Happy coding!

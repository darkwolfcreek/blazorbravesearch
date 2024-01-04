# BlazorBraveSearch

<img src="https://i.imgur.com/8cfTuJj.png" alt="BlazorBraveSearch Interface" width="250"/>

BlazorBraveSearch is a dynamic web application built using the Blazor framework. It showcases the capability to perform searches related to Wizard101, but its flexible design allows for adaptation to various other search domains.

## Features

- **Blazor Framework**: Utilizes Blazor for interactive UIs in C#.
- **Brave Search API**: Implements this API for efficient search result fetching.
- **Adaptable for Various Searches**: Initially focuses on Wizard101, but can be easily adapted for other topics.
- **User-Friendly Interface**: Clean, responsive UI with easy navigation.

## Technology Stack

- **Blazor**: A .NET web framework used for building the application.
- **Brave Search API**: Integrated for handling search queries and results.
- **.NET HttpClient**: For making HTTP requests to the API.
- **WebAssembly**: Enables running C# code in the browser.

## Installation

1. Clone the repository: `git clone [repository URL]`.
2. Navigate to the project directory: `cd BlazorBraveSearch`.
3. Restore dependencies: `dotnet restore`.
4. Run the application: `dotnet run`.

## How It Works

The main interface allows users to enter search queries, which are processed using Brave Search API. The results are displayed in a structured format, with options for filtering and direct links. Users can also search with predefined buttons for specific categories like "Item", "Spell", "Quest", etc.

### Code Highlights

- **Search Functionality**: The application contains functions to handle search queries, both general and prefixed. 
- **Dynamic Result Display**: The UI dynamically updates to show search results or a 'No results found' message.
- **Customizable Whitelist**: Includes a domain whitelist, enhancing the search focus.
- **Error Handling**: Basic error handling is implemented for API calls.

## Contributing

Contributions to enhance BlazorBraveSearch are welcome. Please feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

For any inquiries or contributions, please contact darkwolfcreek2768@hotmail.com.

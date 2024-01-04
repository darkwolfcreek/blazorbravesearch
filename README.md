Great, with the MIT License details provided, here's how you can incorporate it into your README:

# BlazorBraveSearch

<img src="https://i.imgur.com/8cfTuJj.png" alt="BlazorBraveSearch Interface" width="250"/>

BlazorBraveSearch is a dynamic web application built using the Blazor framework. Originally designed for searches related to Wizard101, its flexible design allows for adaptation to various other search domains.

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

MIT License

Copyright (c) 2024 darkwolfcreek

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Contact

For any inquiries or contributions, please contact darkwolfcreek2768@hotmail.com.

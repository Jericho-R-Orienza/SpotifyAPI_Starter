# Spotify Tracker App

The Spotify Tracker App is a lightweight iOS application developed using Swift in Xcode. It connects to Spotify's API to fetch and display the current music a user is listening to, their listening history, and various other stats related to their music consumption. This app is perfect for music enthusiasts who wish to have more insights into their listening habits.

## Features

- **Current Playing Track:** Displays information about the song you are currently listening to on Spotify.
- **Listening History:** Provides a list of tracks you've recently listened to on your Spotify account.
- **Music Statistics:** Offers various statistics about your listening habits, including top artists, most played songs, and genre breakdowns.

## Getting Started

### Prerequisites

- An iOS device or simulator running iOS 13.0 or later.
- Xcode 12 or later installed on your Mac.
- A Spotify Premium account (required for accessing certain features of the Spotify API).

### Installation

1. Clone the repository to your local machine using Xcode 

2. Open the project in Xcode

3. Configure the Spotify API:
   - Visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and create a new application.
   - Note your Client ID and Client Secret.
   - Insert your Client ID and Client Secret into the appropriate fields in the `SpotifyService.swift` file.

4. Run the app on your iOS device or simulator.

## Usage

Once installed, the app requires you to log in with your Spotify account. After authorization, you can:

- View the currently playing track along with artist and album information.
- Access your listening history from the main menu.
- Explore your listening statistics through the Stats tab.

## Contributing

Feel free to use this project for your own educational or devloping purposes!

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


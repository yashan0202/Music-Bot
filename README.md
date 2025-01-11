<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

  <h1>Discord Music Bot</h1>
    
  <h2>Project Overview</h2>
    <p>
        This project is a feature-rich music bot for Discord, built using <strong>Python</strong> and the <code>discord.js</code> library. The bot allows users to play music from multiple sources, including <strong>YouTube</strong>, <strong>SoundCloud</strong>, and <strong>Spotify</strong>, directly in Discord voice channels. It enhances the user experience by enabling easy playback controls and supporting multiple audio formats.
    </p>

  <h2>Features</h2>
    <ul>
        <li><strong>Multi-Platform Music Support</strong>:
            <ul>
                <li><strong>YouTube</strong>: Play music directly from YouTube links or search queries.</li>
                <li><strong>SoundCloud</strong>: Stream music from SoundCloud.</li>
                <li><strong>Spotify</strong>: Integrates with Spotify to fetch and play tracks, playlists, and albums.</li>
            </ul>
        </li>
        <li><strong>Playback Controls</strong>:
            <ul>
                <li><strong>Play</strong>: Start playing music from a specific source.</li>
                <li><strong>Pause</strong>: Pause the current track.</li>
                <li><strong>Resume</strong>: Resume paused playback.</li>
                <li><strong>Skip</strong>: Skip to the next track in the queue.</li>
                <li><strong>Stop</strong>: Stop playback and clear the queue.</li>
            </ul>
        </li>
        <li><strong>Queue System</strong>: Add multiple tracks to a queue and manage their order.</li>
        <li><strong>Volume Control</strong>: Adjust the playback volume for all users in the voice channel.</li>
        <li><strong>Dynamic Interaction</strong>: Users can control the bot using text commands in chat.</li>
    </ul>

  <h2>Technologies Used</h2>
    <ul>
        <li><strong>Programming Language</strong>: Python</li>
        <li><strong>Library</strong>: discord.js</li>
        <li><strong>Additional Tools</strong>: FFmpeg for audio processing, YouTube API, and Spotify API integration.</li>
    </ul>

  <h2>Project Structure</h2>
    <ul>
        <li><strong>Commands</strong>: Includes modular command files for handling bot commands like play, pause, skip, and more.</li>
        <li><strong>Music Player</strong>: Core logic for managing playback, queues, and audio streaming.</li>
        <li><strong>API Integration</strong>: Modules for interacting with YouTube and Spotify APIs to fetch track details and streams.</li>
    </ul>

  <h2>How It Works</h2>
    <ol>
        <li><strong>Initialization</strong>: The bot connects to the Discord server and listens for user commands in specific text channels.</li>
        <li><strong>Command Handling</strong>: 
            <ul>
                <li>Users input commands (e.g., <code>!play [song name or link]</code>).</li>
                <li>The bot processes the command and fetches the requested track using the appropriate API.</li>
            </ul>
        </li>
        <li><strong>Audio Streaming</strong>: 
            <ul>
                <li>The bot streams audio to the voice channel in real-time using FFmpeg and Discord's audio protocol.</li>
                <li>Tracks are queued and played sequentially.</li>
            </ul>
        </li>
        <li><strong>Interactive Controls</strong>: Users can pause, skip, or stop the playback using simple commands.</li>
    </ol>

  <h2>Error Handling</h2>
    <ul>
        <li><strong>Invalid Commands</strong>: Provides user-friendly error messages for unrecognized or invalid commands.</li>
        <li><strong>API Errors</strong>: Handles issues with YouTube, SoundCloud, or Spotify API responses.</li>
        <li><strong>Voice Channel Issues</strong>: Alerts users if the bot fails to connect to a voice channel or if the channel is empty.</li>
    </ul>

  <h2>Future Enhancements</h2>
    <ul>
        <li>Adding playlist management features for creating and saving custom playlists.</li>
        <li>Improving search capabilities for more accurate song selections.</li>
        <li>Integrating lyrics fetching functionality to display song lyrics in chat.</li>
        <li>Supporting additional audio sources like Apple Music.</li>
    </ul>

  <h2>Getting Started</h2>
    <p>To set up and run the bot locally:</p>
    <ol>
        <li>Clone the repository to your local machine.</li>
        <li>Install required dependencies using <code>npm install</code>.</li>
        <li>Set up a Discord bot account and retrieve the token from the <a href="https://discord.com/developers/applications">Discord Developer Portal</a>.</li>
        <li>Configure API keys for YouTube and Spotify in the bot's configuration file.</li>
        <li>Run the bot using <code>node index.js</code>.</li>
    </ol>

<h2>Prerequisites</h2>
    <ul>
        <li><strong>Node.js</strong>: Install Node.js and npm on your system.</li>
        <li><strong>FFmpeg</strong>: Ensure FFmpeg is installed for audio processing.</li>
        <li><strong>Discord Bot Token</strong>: Create a bot on the Discord Developer Portal and obtain a token.</li>
    </ul>

  <h2> Developed by: Yash Anand </h2>

</body>
</html>

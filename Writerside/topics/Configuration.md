# Configuration

The configuration file is a JSON file that contains all the **settings** for the video generation.

## Configuration File

The configuration file is named `config.json` and is located in the config directory of the project. It is a JSON file that contains all the settings for the video generation.

## Configuration Options

The following options are available in the configuration file:

- `assembly_ai_api_key`: The API key for the AssemblyAI service.
- `font`: The path to the font file to use for the text overlay.
- `font_size`: The size of the font to use for the text overlay.
- `font_color`: The color of the font to use for the text overlay.
- `font_background_color`: The background color of the font to use for the text overlay.
- `threads`: The number of threads to use for the video generation.
- `transcribe`: Whether to transcribe the audio of the video.
- `satisfying`: The path to the satisfying video to use for the video generation.
- `music`: The path to the music to use for the video generation.
- `music_volume`: The volume of the music to use for the video generation.
- `width`: The width of the video to generate.
- `height`: The height of the video to generate.
- `fps`: The frames per second of the video to generate.


## Exemple

```json
{
  "assembly_ai_api_key": "fe8W5....gV5pO",
  "font": "assets/fonts/LeagueSpartan-Bold.ttf",
  "font_size": 24,
  "font_color": "white",
  "font_background_color": "black",
  "threads": 8,

  "transcribe": true,
  "satisfying": "",
  "music": "",
  "music_volume": 0.5,
  "width": 540,
  "height": 960,
  "fps": 24
}
```
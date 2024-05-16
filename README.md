# Omniscient
<img src="docs/imgs/omnisient_logo.webp" alt="Omniscient logo" width="300">

Omniscient is an AI tool designed to enhance daily cognition through speech pattern analysis, providing insights into an individual's cognitive state.

## Overview

Omniscient processes data through several layers:

1. **Audio Data Collection**: Uses a Rode Wireless Mic 2 to collect audio data throughout the day.
2. **Data Upload**: Audio data is uploaded to the Omniscient platform.
3. **Transcription**: Utilizes OpenAI's open-sourced transcription model, "Whisper", to convert audio to text.
4. **Speaker Diarization**: Employs Pyannote's audio model to distinguish speakers. The primary user must speak first in the recording for accurate identification.
5. **Data Synchronization and Labeling**: Syncs and labels the transcription and diarization data to maintain context and speaker identity.
6. **Cognitive Analysis**: Analyzes the data using the `Llama70b` model by default. Customizing metrics is straightforward—see the [documentation here]() for prompt modification instructions.
7. **Data Export**: Exports the analyzed data metrics to a CSV file for further analysis.

### Integration

Omniscient is integrated into the [ESC Velocity]() project, enhancing the insights provided by Omniscient. Visit the ESC Velocity project page for more information and additional features.

## Getting Started

To use Omniscient, follow these steps:

1. Set up your Rode Wireless Mic 2 for audio data collection.
2. Install the necessary dependencies and set up the Omniscient platform as described in our [setup guide]().
3. Consult the [user manual]() for detailed operating instructions and how to customize your analysis metrics.

## Contributions

We welcome contributions to Omniscient. If you wish to improve the tool or add features, please refer to our [contribution guidelines]().

## License

Omniscient is released under the [MIT License](). See the LICENSE file for more details.

## Contact

For support or feedback, contact us through our [support channel]().
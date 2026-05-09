The documentation for translation is [here](https://github.com/vcmi/vcmi/blob/develop/docs/translators/Translations.md).

Information for dubbing are [here](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)

Please create a new issue [here](https://github.com/vcmi-mods/dutch-translation/issues/new) for any mistake.

# How to play to Heroes of Might and Magic III in Dutch

1. Buy _Heroes of Might and Magic III Complete Edition_ on GOG (not the HD version)
1. Install the game
1. Download VCMI (free)
1. Install VCMI
1. When installing VCMI, specify the location of the base game's `Data`, `MP3`, and `Maps` folders.
1. Set the language to _Dutch_
1. Install the _Nederlandse vertaling_ mod
1. Launch the game

# Hoe speel je Heroes of Might and Magic III in het Nederlands?

1. Koop _Heroes of Might and Magic III Complete Edition_ op GOG (niet de HD-versie)
1. Installeer het spel
1. Download VCMI (gratis)
1. Installeer VCMI
1. Geef tijdens de installatie van VCMI de locatie op van de mappen `Data`, `MP3` en `Maps` van het basisspel.

1. Stel de taal in op _Nederlands_
1. Installeer de _Nederlandse vertaling_ mod
1. Start het spel

# How to dub

1. Copy a prolog/epilog from [`content/config/vcmi-dutch/campaigns.json`](https://github.com/vcmi-mods/dutch-translation/tree/vcmi-1.7/content/config/vcmi-dutch/campaigns.json) or [mods/AITranslated/Content/config/vcmi-dutch-ai/campaigns.json](https://github.com/vcmi-mods/dutch-translation/blob/vcmi-1.7/mods/AITranslated/Content/config/vcmi-dutch-ai/campaigns.json)
2. Go to [_XTTS_](https://huggingface.co/spaces/Fabrice-TIERCELIN/Multi-language_Text-to-Speech)
3. Paste the speech text
5. Select _Dutch_
4. Upload a voice
4. Set the output number to `9`
5. Click on _Speak_
6. Download the audio files
7. Select the best file or mix them using _Audacity_
8. Retrieve the property for the speech in the [`content/config/vcmi-dutch/campaigns.json`](https://github.com/vcmi-mods/dutch-translation/tree/vcmi-1.7/content/config/vcmi-dutch/campaigns.json) or [mods/AITranslated/Content/config/vcmi-dutch-ai/campaigns.json](https://github.com/vcmi-mods/dutch-translation/blob/vcmi-1.7/mods/AITranslated/Content/config/vcmi-dutch-ai/campaigns.json) file
9. Retrieve the related audio filename in the [empty-translation mod](https://github.com/vcmi-mods/empty-translation?tab=readme-ov-file#dubbing)
10. Rename the audio file
11. Move the file to `content/sounds/` folder

# Mixxx-Pioneer-DDJ-SB3
Mixxx  controller mappings for the Pioneer DDJ SB3

These files are based on the DDJ-SB2 files that are part of the Mixxx distribution: https://github.com/mixxxdj/mixxx/tree/master/res/controllers

## Midi Message Lists
* Midi Message List for the SB3 (PDF): https://www.pioneerdj.com/-/media/pioneerdj/software-info/controller/ddj-sb3/ddj-sb3_midi_message_list_e1.pdf
* Midi Message List for the SB2 (PDF), for comparison against SB3: http://faq.pioneerdj.com/files/img/DDJ-SB2_List_of_MIDI_Messages_E.pdf

## Running the Tests
1. Install Node
2. Install Yarn
3. Install Jest
4. run yarn test

## Feature Matrix
Here we try and list what is working and what isn't

| Feature      | Deck 1  | Deck 2  | Deck 3  | Deck 4  |
|--------------|---------|---------|---------|---------|
| Play / Pause | Yes     | Yes     | No      | No      |
| Cue          | Yes     | Yes     | No      | No      |
| Key Lock     | Yes     | Yes     | No      | No      |
| Sync         | Partial | Partial | No      | No      |
| FX Fade      | Partial | Partial | No      | No      |
| Auto Loop    | Yes     | Yes     | No      | No      |   
# Kaltura
King's Digital styling is applied to the Kaltura v7 video and audio players through a single stylesheet via the Kaltura Management Console (KMC).

## Workflow and deployment
CSS updates are tested on King’s E-Learning and Teaching Service (KEATS) through the following workflow:

1. Update the `v7-players-dev.css` file. Changes should be visible on KEATS UAT through the KD UATDEV players
2. Conduct tests on the KD UATDEV players, paying attention to how the player appearance changes upon page load and after initial interaction, and across varying device widths
3. Once satisfied with the changes, contact Charles Kasule to inform him that changes are due to be applied
4. Finally, copy the contents of `v7-players-dev.css` to `v7-players.css`. This will apply changes to the stable players in UAT as well as the two live players. 

## Player skins and environments
| Player KEATS environment | Player skin ID | Player name            | Description             | Linked CSS file    |
| ------------------------ | -------------- | ---------------------- | ----------------------- | ------------------ |
| Production               | 54613962       | KD Player Live         | Production video player | v7-players.css     |
| Production               | 54614062       | KD Audio Player Live   | Production audio player | v7-players.css     |
| UAT                      | 54423492       | KD UAT video player    | UAT stable video player | v7-players.css     |
| UAT                      | 54574542       | KD UAT audio player    | UAT stable video player | v7-players.css     |
| UAT                      | 58131142       | KD UATDEV video player | UAT dev video player    | v7-players-dev.css |
| UAT                      | 58135132       | KD UATDEV audio player | UAT dev audio player    | v7-players-dev.css |

# python-rtmbot-hodor
### Slack rtmbot plugin designed for hodoring.

Plugin for [python-rtmbot](https://github.com/slackhq/python-rtmbot) : listen for mentions of Hodor's name in slack channels and reply with a message.

Messages are pre-defined from a basic module import and classified by mood.

The 'mood' of reply is determined by comparing the content of the triggering
message against a library of words and human interpreted intent scoring. After
mood assignment, a message is chosen based on a 'item drop' type selection process
that allows for weighting of responses.

##License
- python-rtmbot-hodor is licensed under the MIT License:
  - http://opensource.org/licenses/mit-license.html
- Attribution is not required, but much appreciated:
  - `python-rtmbot-hodor by Jacob Sanford`

## Sources
- Mood is chosen based on a dataset 'AFINN' generated by Finn Arup Nielsen in
2009-2011 and used under the "Open Database License (ODbL) v1.0". http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010
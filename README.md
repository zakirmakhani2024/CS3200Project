# LivePlat

Project Name: LivePlat
Team: Zakir Makhani


Problem statement: Very limited options in terms of live streaming content available online (mainly only Twitch and Youtube). Creators cna force themselves into only working for on one of these platforms, with little room for negotition for contracts. Furthermore, features unwanted in these streaming sites, such as certain chat functions or the ability to boost one's stream that are undesired limit the joy for both users and creators.

Solution: Provide a new livestreaming platform with more accessible features for both users and creators to be competitive with these platforms.

Description: LivePlat is a typical livestreaming platform (similar to Twitch). Users can watch ongoing livedtreams, comment in chat, and make clips from content from the stream. It will not be an actual livestreaming platform, just aa skeleton of one such platform.
Link to UML Diagram: https://lucid.app/lucidchart/5588b4ad-3496-4a2f-b806-2f253c720d9a/edit?invitationId=inv_9dd2df17-c238-43ce-88af-982aafd193cd
Description of User Data Model: Users can create account as long as they provide the following credentials, first name, last name, username, password, email, and (optionally) their date of birth. For simplicity sake, users will only view one stream at a time and there will be no VODs on the platform so there is only one existing stream at most, as well as chat and view clips of each of those streams. Many users can watch a single stream at a time. Users are associated with a unique livestream of their own.
Description of Livestream Data Model: The most relevant values of any particular livestream is the number of people watching and the length of the current stream, as indicated by the viewers and seconds values respectively. The title of the livestream is also important to get users to join the livestream. From these livestreams, users can make clips from the stream, as well as comment on them through the chat. A single livestream can have many users viewing, chat messages, and clips.
Description of Clips Data Model: When viewing a clip, the most important attributes are the length of the clip and the number of views this clip has, as indicated by the seconds and views value respectively. Once again, the titleof the clip is also a nice value to have for user engagement. Multiple clips can come from a single livestream.
Description of Chat Data Model: Chat messages make a significant factor of the livestream experience as interatcion between the viewer and streamer. These interactions are encapuslated within the content attribute. A single livestream can, and usually does, have many chat messages, and users can make many messages. Emotes are included within the chatting experience, hence the emote enumeration within the attributes, which includes three emotes.
Description of User Interface: Users can click from a list of existing streamers to see if they are currrently streaming or not, and are able to type in chat. They are also able to view clips from the stream from the stream page.

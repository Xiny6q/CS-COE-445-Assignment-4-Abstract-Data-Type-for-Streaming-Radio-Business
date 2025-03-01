Download link :https://programming.engineering/product/cs-coe-445-assignment-4-abstract-data-type-for-streaming-radio-business/

# CS-COE-445-Assignment-4-Abstract-Data-Type-for-Streaming-Radio-Business
CS/COE 445 Assignment 4 Abstract Data Type for Streaming Radio Business
Imagine that you are starting a streaming radio business. Partnerships have been established to provide you with audio content, and you will stream that content to users. You plan to use your knowledge of what songs your users like/dislike to make effective suggestions for new songs that they will like.

In this assignment, you will be designing an abstract data type (ADT) for storing the service’s music library and users’ ratings of songs. This ADT will be used by client applications as well as for administrative uses (like adding new songs to the library). Once you complete this ADT, you could provide it to the programmers of the client applications, and they will be able to develop applications based on this specification. You could also distribute the ADT interface to the programmers in charge of implementing the functionality of the data structure – like what you did with the PrimQ and Reorder interfaces in Assignment 1 and 2 and with the SolutionInterface and DecisionInterface interfaces in Assignment 3. Then these two groups (client programmers and data structure developers) can work in parallel on their respective components; the code of the resulting components will integrate since it follows the “contract” that your ADT provides.

You will specify the full set of details that a client needs to know in order to use the data structure. You do not need to consider implementation-level details, since you are only writing the ADT interface. So, you should not specify the details of how the operations will be carried out or how the data will be organized in memory. The implementation details should be left up to the implementers.

DETAILS



You must write an abstract data type as a Java interface. We have given you the names of several abstract methods that the data structure would need to support. You must specify them in the Javadoc comments above each method.


You should consider all possible corner cases in your specification and describe what the class should do in all cases. A client that reads your ADT should know all the things that could go wrong, and how each will be handled.

Error cases should be unambiguous to the client, and the client should always know which specific error was encountered. For some corner cases, you will need to make a design decision regarding the best way to handle them. You have the freedom to make these decisions any way you wish as long as you are consistent, thorough, and clear in your descriptions.

Remember that in Javadoc we document parameters by using the @param name command, return values with @return, and exceptions with @throws name.

The following files that are provided to you:

StreamingRadio.java – The interface that you will modify.

User.java, Song.java, and Station.java – Provided for you to use as return types and parameters in StreamingRadio. You do not need to modify these files.

src/doc – Directory containing the Javadoc. Open index.html to see the documentation.

There are 8 methods in the StreamingRadio ADT. One of them has been specified for you, as an example of the kind of specification we are looking for. So, you must complete the specification of the remaining seven methods. You will be adding parameters, return types, and exceptions to throw to each. Each one has a short description in StreamingRadio.java, so read those.

addSong

removeSong

addToStation

removeFromStation

rateSong

clearRating (This one has been completed for you. You can change it for your needs, if you want.)

predictRating

suggestSong

You are not required to write implementations of these methods.

NOTES



Assume that the set of users and radio stations are fixed. That way, you do not need to include operations to change the collections.

3

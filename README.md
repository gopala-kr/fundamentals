


<p>NLP capabilities:</p>
<ul>
<li><strong>Automatic speech recognition (ASR)</strong>, which converts what you say into computer-readable text, also called "speech to text"</li>
<li><strong>Text to speech</strong>, which goes the other way and gives computer an increasingly human-sounding voice</li>
<li><strong>Language detection</strong> which figures out what language a document is written in</li>
<li><strong>Machine translation</strong>, which translates text from any language to any language. Some language pairs work better than others, mostly because of the availability of data sets.</li>
<li><strong>Sentiment analysis</strong>, which figures out the emotional tilt of text</li>
<li><strong>Entity extraction</strong>, which highlights all the "things, places, people, and products" in a piece of text</li>
<li><strong>Information extraction</strong>, which finds relationships between extracted entities, such as "who did what to whom and how did they do it"?</li>
<li><strong>Document analysis</strong>, which categorizes documents, figures out what they are talking about (topic modeling), and makes the content easy to search (find documents about "fund raising" even if the documents never contain that exact phrase)</li>
<li><strong>Natural language generation</strong>, which generates well-formed sentences so that when you are chatting with your bot, it sounds like a real person</li>
<li><strong>Summarization</strong>, which generates readable summaries of arbitrary text documents, preserving as much of the meaning as possible</li>
<li><strong>Question answering</strong>, which answers questions from people about a dataset. Part of the challenge is figuring out which questions mean the same thing. In bots, a hot topic these days is "intent categorization", which is about trying to figure out what the user is trying to accomplish (e.g., book a flight, schedule a meeting, make a withdrawal)</li>
</ul>
<p>Let's explore a few of these capabilities by calling real-world APIs, some from the open source community and others from the major public cloud providers such as Google, Microsoft, and IBM. You can type your own sentence or use of our pre-canned examples. Check the"I'm not a robot" box, and hit analyze. Click on the API Name to see the results that come back. It's fun! For example, click the IBM Watson Developer Cloud answer for sentiment analysis. It's like the entire cast (and friends) of Pixar's <a href="http://www.imdb.com/title/tt2096673/"><em>Inside Out</em></a> is evaluating your sentence.</p>
<p>Also, a quick shout out to the fabulous Delip Rao (<a href="http://twitter.com/deliprao">@deliprao</a>) of <a href="http://joostware.com/">Joostware</a> for his review of this entire guide, but especially this section. Delip knows NLP, among many other AI technologies. Thanks, Delip!</p>
<h2 id="user-content-sentimentanalysis">Sentiment Analysis</h2>
<p>A common natural language processing task involves understanding the affect or sentiment of text, also known as sentiment analysis. For example, the following sentences:</p>
<ul>
<li>"Seeing the F-117 Nighthawk was cool."</li>
<li>"Airplanes with the shape of hawks are cool."</li>
<li>"Seeing a hawk flying at night is cool."</li>
</ul>

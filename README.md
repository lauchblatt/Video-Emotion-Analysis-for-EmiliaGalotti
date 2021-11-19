# Corpus material for the paper Exploring Multimodal Sentiment Analysis in Plays: A Case Study for a Theater Recording of Emilia Galotti
This is a GitHub repository for the paper <a href="http://ceur-ws.org/Vol-2989/short_paper45.pdf">Exploring Multimodal Sentiment Analysis in Plays: A Case Study for a Theater Recording of Emilia Galotti</a> that was presented at <a href="https://2021.computational-humanities-research.org/">Second Conference on Computational Humanities Research (CHR 2021)</a>.

This repository hosts the annotation as well as results of the sentiment prediction in a table in csv-format. Each row represents a video unit as explained in the paper. Due to legal constraints, we cannot publish the video, video snippets, images or audio files. If you need access to these files you have to contact me via mail: thomas.schmidt@ur.de

Please cite the paper if you use or reference this corpus in any form:
Schmidt, T., & Wolff, C. (2021). Exploring Multimodal Sentiment Analysis in Plays: A Case Study for a Theater Recording of Emilia Galotti. Proceedings of the Conference on Computational Humanities Research 2021 (CHR 2021). Amsterdam, Netherlands. <a href="http://ceur-ws.org/Vol-2989/short_paper45.pdf">[pdf]</a> <a href="https://www.researchgate.net/publication/355912809_Exploring_Multimodal_Sentiment_Analysis_in_Plays_A_Case_Study_for_a_Theater_Recording_of_Emilia_Galotti">[researchgate]</a>  <a href="https://youtu.be/PzvPh1K_pWk">[youtube]</a> 

Structure of the csv-file:
<ul>
  <li>Number of video: An ID used for analysis</li>
  <li>Text: Text spoken in this video snippes</li>
  <li>Annotation: The final annotation of the annotators for the three classes positive, negative, neutral.</li>
  <li>Textual_Sentiment_Analysis: Classification of the textual sentiment analysis </li>
  <li>Audio_Sentiment_Analysis: Classification of the audio sentiment analysis</li>
  <li>Video_Sentiment_Analysis: Classification of the image-based sentiment analysis</li>
  <li>Start_Frame: First image to define the used images for the analysis.</li>
  <li>End_Frame: Last image to define the used images for the analysis.</li>
</ul> 

If you are interested in similar text-based corpora please take a look at this <a href="https://github.com/lauchblatt/LessingSentimentEmotionCorpus">repository</a>.

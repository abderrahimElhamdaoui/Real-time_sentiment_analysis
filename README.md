<!DOCTYPE html>
<html>
    <body>
        <h1>L'extraction et l'analyse des tweets en temps réel</h1>
        <p>
            <h3>Ce projet analyse les sentiments en temps réel à partir de flux de données, tels que des tweets. L'application utilise des techniques de traitement du langage naturel (NLP) pour déterminer les sentiments positifs, négatifs ou neutres des textes analysés.</h3>
          <h3>Le projet est divisé en deux parties</h3>
          <ul>
            <li> **Extraction des tweets** : Le code utilise Selenium pour automatiser l'interaction avec Twitter et récupérer les tweets en temps réel.</li>
            <li> **Analyse des sentiments** : Le code analyse les sentiments des tweets récupérés en utilisant des techniques de traitement du langage naturel (NLP).</li>
          </ul>
        </p>

        <h3> I. Le code d'extraction des tweets utilise Selenium pour automatiser l'interaction avec Twitter et récupérer les tweets en temps réel</h3>
          <h4>Fonctionnalités</h4>
          <ul>
            <li>Extraction des tweets en temps réel</li>
            <li>Stockage des tweets dans MongoDB</li>
            <li>Analyse des sentiments des tweets</li>
          </ul>
          <h4>Prérequis</h4>
          <ul>
            <li>Python 3.x</li>
            <li>MongoDB</li>
            <li>Selenium</li>
            <li>Webdriver pour Microsoft Edge</li>
            <li>Git</li>
            <li>Compte Twitter avec les informations d'identification</li>
          </ul>

        <h3> II. Analyse de sentiments sur les tweets</h3>
         <h4>Fonctionnalités</h4>
           <ul>
            <li>Extraction des tweets à partir de MongoDB</li>
            <li>Nettoyage des tweets (conversion en minuscules, suppression des ponctuations, des emojis, des mots vides)</li>
            <li>Analyse des sentiments des tweets en utilisant un modèle pré-entraîné de Hugging Face Transformers</li>
            <li>Visualisation des résultats (diagrammes circulaires, histogrammes)</li>
           </ul>

         <h4>Prérequis</h4>
          <ul>
            <li>Python 3.x</li>
            <li>MongoDB</li>
            <li>nltk</li>
            <li>seaborn</li>
            <li>missingno</li>
            <li>matplotlib</li>
            <li>wordcloud</li>
            <li>transformers</li>
          </ul>

    </body>
</html>

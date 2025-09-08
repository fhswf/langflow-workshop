<a href="https://www.ki.fh-swf.de/new-jupyterhub/hub/user-redirect/git-pull?profile=langflow&repo=https%3A%2F%2Fgithub.com%2Ffhswf%2Flangflow-workshop.git&branch=main&profile=langflow" style=""><img src="https://www.ki.fh-swf.de/cluster_badge.svg" style="height: 32px" alt="Open in FH Cluster"></a>


# KI mit Spickzettel: Wie macht man Wissen für LLMs zugänglich?

## Recherche mit Google oder dem [K!mpuls Chatbot](https://openai.ki.fh-swf.de)

Versuchen Sie, folgende Fragen zu beantworten:

- Wie lange dauert eine Bachelorarbeit im Studiengang Informatik?
- Welche Module unterrichtet Prof. Christian Gawron?
- Welche Module gehören zur Vertiefungsrichtung Künstliche Intelligenz?
- ... weitere Fragen zum Studiengang Informatik

## Umsetzung einer RAG-Pipeline mit [Langflow](https://www.langflow.org/)

Wir setzen eine RAG-Pipeline (Retrieval-Augmented Generation) mit Langflow um, um Fragen mithilfe von Dokumenten zu beantworten. Wir wollen dazu 

- das Modulhandbuch 
- und die Fachprüfungsordnung 

für den Studiengang Informatik verwenden.

### 1. Starten Sie Langflow

![Screenshot](./img/Screenshot_1.png)

### 2. Importieren Sie den Flow `Vector Store RAG mit Chroma.json`

![Screenshot](./img/Screenshot_2.png)

Anschließend sollte folgender Flow in Langflow angezeigt werden:

![Screenshot](./img/Screenshot_3.png)

### 3. Fügen Sie die Dokumente hinzu

Die Dokumente finden Sie im Verzeichnis `example_docs`.

### 4. Öffnen Sie den *Playground* und testen Sie die RAG-Pipeline mit den Fragen.

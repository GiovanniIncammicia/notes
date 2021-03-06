# Blog

## Tipi di post
* How to articles and tutorials
* Checklists
* Lists or listicles
* Comparison posts
* Interviews
* Long-form blog posts with deep research
* Roundup posts
* Expert advice

## Ispirazione per l'argomento (e.g. dieta Keto)
* How to get started with Keto
* A checklist of how to make their pantry keto friendly
* 7 tips to make it through the Keto Flu
* Keto vs. Mediterranean diet
* An interview with a top Keto blogger
* Deep research on the health benefits of Keto
* Roundup of the best fat bombs
* Expert advice for curbing carb cravings

## Come scrivere un outline
1. [[Scegli il tuo "working title"]]
2. [[Scrivi tutti i "takeaways" che ti vengono in mente]]
3. [[Raccogli i "takeaways" in sezioni]]
4. [[Aggiungi più "takeaways" alle sezioni]]
5. [[Riguarda, rimuovi e riorganizza i dettagli di ogni sezione]]
6. [[Aggiungi esempi e link]]
7. [[Aggiungi qualsiasi dettaglio ti venga in mente]]

## Tipi di headline
* **The list headline:** You’ve seen so many of these you probably don’t even notice them anymore. But people still respond well to it. Example: 100 Things to Do Instead of Going on Social Media
* **The Clickbait:** Everyone hates these, but they still work for some reason. We just can’t resist. They tend to be a bit controversial, weird, or shocking. Example: You won’t believe what happened when this fox encountered a house cat.
* **The Ultimate:** These are the guide headlines that show they are a huge roundup of information on a specific topic. For Example: The Ultimate Guide to Email Marketing for Bloggers
* **The Best Of:** These tend to be roundup posts where you’re trying to give a lot of information like the top services, products, or people. For example: 25 Best WordPress Plugins for Bloggers.
* **Learn from My Mistakes:** This helps people learn from the mistakes you’ve made so they can skip past the trial and error phase you had to go through. Example: 10 Mistakes I Made When I First Started Freelance Writing

## Suggerimenti
* **50% del tempo** dovrebbe essere speso a **pianificare il post (ricerca e outline)**
* **20% del tempo** dovrebbe essere speso a **scrivere la bozza**
* **30% del tempo** dovrebbe essere speso a **sistemare e revisionare il testo**
* Scrivi paragrafi da massimo 7 righe
* Usa verbi forti per sostenere la frase
* Non iniziare con "c'è" o "ci sono". Trova il vero soggetto della frase e inizia con quello
* Usa tempi verbali attivi più che passivi
* Evita espressioni gergali o parole che escludono classi di persone (usa persona, invece che uomo/donna)
* Usa paragrafi da una frase sola quando necessario. Rimangono più impressi e aiutano la lettura
* Evita di usare "io penso", "Io credo" e simili. Scrivi con più sicurezza un "Io consiglio"
* Inizia a scrivere dalle parti più facili del post

## Servizi
[Google Trends - confronta la popolarità di parole chiave](https://trends.google.com/trends)  
[Ahrefs - SEO suite](https://ahrefs.com)  
[Wordable - Estrai post per Wordpress da un documento su Google Doc](https://www.wordable.io)  
[BuzzSumo - SEO suite](https://buzzsumo.com)  
[Controlla copyright immagini](https://www.pixsy.com/academy/image-user/verify-image-source-copyright-owner/)  
[Headlines CoSchedule](https://https://headlines.coschedule.com/headlines)

## Come installare una versione locale di wordpress con Docker
* [Installare Docker Desktop](https://www.docker.com/products/docker-desktop)
* Scaricare l'immagine docker per il database mysql: `docker pull mysql`
* Scaricare l'immagine docker per wordpress: `docker pull wordpress`
* Far partire il database: `docker run --name wordpressdb -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=wordpress -d mysql`
* Far partire wordpress: `docker run --name local-wordpress -p 8080:80 -e WORDPRESS_DB_PASSWORD=password --link wordpressdb:mysql -d wordpress`

## References:
[How to write a blog post outline](https://blog.hubspot.com/marketing/how-to-write-blog-post-outline)  
[How to write a blog post outline 2](https://blogfromthebeginning.com/how-to-write-a-blog-post-outline)  
[How to write a blog post](https://ahrefs.com/blog/how-to-write-a-blog-post)  


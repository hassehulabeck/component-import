Ett exempel på hur man i Vue kan använda JS import och export för att separera componenter och HTML.

För att det här ska fungera behöver du förmodligen en webbserver. Du kan ladda ner MAMP (mamp.info) och sedan lägga de här filerna i en egen katalog som du lägger i katalogen MAMP/htdocs

För att se sidan behöver du därefter:
1. Starta MAMP.
2. Öppna en webbläsare och skriva in adressen: localhost/namn-på-egen-katalog/import.html

Om du inte ser något, så kan det bero på att MAMP inte använder standardporten 80 för webbtrafik. Klicka i så fall på "ports" och se om du där hittar ett avvikande nummer. Om du t ex hittar 8888 skriver du adressen:

localhost:8888/namn-på-egen-katalog/import.html

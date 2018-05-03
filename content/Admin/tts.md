+++
title = "Textersetzung für TTS"
weight = 2
+++


![](/img/admin_tts.png?classes=shadow)


Die Abkürzung „TTS“ steht für **T**ext-**t**o-**S**peech (Automatische
Umwandlung von Schreibtext zu Sprechtext).  Geben Sie dazu den zu ersetzenden Text in das Feld „Text“ ein, und den Text der gesprochen werden 
soll in das Feld „Sprechtext“. Wählen Sie dann die Sprache aus, für die die Textersetzung gelten soll.


TTS bietet sich z.B. für Fälle an, in denen sich die Schreibweise bestimmter Begriffe von ihrer
Aussprache unterscheidet.  
 
Darüber hinaus kann der Benutzer hier alle Abkürzungen definieren, die bei einer
Sprach-Alarmübertragung vollständig ausgesprochen werden.  

 - **Beispiel**: <img src="/img/admin_tts_bsp1.png" alt="tts" style='vertical-align:middle;display:inline;margin:0px 5px; '> 

 {{% panel theme="danger" header="Achtung!" %}}Beachten Sie, dass auf Gross- und Kleinschreibung geachtet wird. „GA“ würde in diesem Fall nicht ersetzt werden.
 
 Weiterhin wird jedes Vorkommen des definierten Textes ersetzt. In diesem Fall würde auch im Wort „Auf**ga**be“ das „ga“ ersetzt werden, d.h. das Wort wird zu „Auf**GroupAlarm**be“.{{% /panel %}}
 
   
	

Nutzen Sie daher das Zeichen *Underscore* „_“ , mit dem genauere Textersetzungen vorgenommen werden können:

 - _Wort: ersetzt Wortteile die mit Wort beginnen  
 
	**Beispiel**:<img src="/img/admin_tts_bsp2.png" alt="tts" style='vertical-align:middle;display:inline;margin:0px 5px; '>
	
	Ersetzt in allen Wörtern, die mit „fw“ beginnen, das „fw“ durch „Feuerwehr“. Aus „**fw**wagen“ wird somit „**Feuerwehr**wagen“ 
	
 - Wort_: ersetzt Wortteile die mit Wort enden
 
    **Beispiel**:<img src="/img/admin_tts_bsp3.png" alt="tts" style='vertical-align:middle;display:inline;margin:0px 5px; '>
	
	Ersetzt in allen Wörten, die auf „wg“ enden, das „wg“ durch „wagen“. Aus „Kranken**wg**“ wird somit „Kranken**wagen**“
	
 - _Wort_: ersetzt nur das Wort „Wort“ (alleinstehend)
 
	**Beispiel**:<img src="/img/admin_tts_bsp4.png" alt="tts" style='vertical-align:middle;display:inline;margin:0px 5px; '>
	
	Ersetzt das **alleinige** Vorkommen von „RTW“ durch „Rettungswagen“. „RTWs“ wird somit hier **nicht** zu „Rettungswagen“ 


Mit der Testzeile können Sie direkt die Umsetzung ihrer Eingaben testen. Geben Sie dazu einen Text in die Testzeile und wählen Sie die Sprache, dann wird
in der Zeile „Ausgabe“ die entsprechende Umwandlung angezeigt.

![](/img/admin_tts_testzeile.png?classes=shadow)





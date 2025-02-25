25.02.2025: Since github is a bit much overhead I am trying a combination of Mixa and Obsidian for gathering  new notes on accessibility: https://a11y.mixa.site/ 


08.2022: **Thank you to all who helped me with this survey/thesis!** I could not have done it without your participation/support.

In this thesis, the requirements of developers and people close to development for a national accessibility information source (AX) in Switzerland are investigated. The findings are intended to serve as a basis for discussion of next steps.
The 94 participants of the anonymous survey indicated lack of time, skills and awareness as the main reasons for not implementing accessibility. Awareness measures were the top areas in need of further development. Many participants were not familiar with existing resources such as the Swiss Accessibility Standard eCH-0059 and the Accessibility Developer Guide. From a literature review on the AX curriculum and an analysis of AX information sites, a matrix was created showing that the subtopics of the AX curriculum are already all covered in information sites.

 <br> <br>
____

 <br> <br> <br>

# Einführung und Lizenz

Die auf dieser Seite präsentierte Information wurde im Rahmen einer Bachelorarbeit eines [PiBS Informatik-Studiums an der Fernfachhochschule Schweiz - FFHS](https://www.ffhs.ch/de/bachelor/praxisintegriertes-bachelor-studium-informatik-pibs) erstellt. Alle Rechte gehören der FFHS und müssen entsprechend ausgewiesen und referenziert werden.

# Umfrageresultate 
(09.08.2022) <br>
Durch die Teilnahme von 94 Personen an der im Mai 2022 durchgeführten Umfrage konnten Einblicke in die Meinungen von Entwicklern und entwicklungsnahen Personen in der Schweiz über den Stand des Lernens über die Entwicklung von barrierefreien Webprodukten gewonnen werden. Herzlichen Dank an alle Teilnehmer! 

Folgend drei Dokumente mit der in der Umfrage und Bachelorarbeit gefundenen Information zu Informationsseiten zu Accessibility für Entwickler:

* [PDF-Dokument mit den Resultaten der Umfrage in Textform (Auszug aus der Bachelor-Thesis)](UmfrageresultateAbklaerungNationaleAX-Informationsquelle_v2.pdf)


* [PDF-Dokument mit der Ressourcensammlung: Auflistung und Beschreibung der im Rahmen dieser Analyse gefundenen Informationsseiten für Entwickler zu Accessibility](AXBedarfsabklaerung-Ressourcensammlung_MayaHartmeier_mitLinks.pdf)

* [Alle Detailantworten der anonymen Umfrage als Excel-Dokument](AXBedarfsabklaerung-Umfrageresultate_MayaHartmeier.xlsx)



<br><br><br>

# Accessibility (AX) - A11y: In a nutshell
Barrier-free web content is accessible to people with disabilities. Accessibility involves a wide range of disabilities:
- Physical: Visual, auditory, motor, speech
- Mental: Cognitive, language, learning, and neurological disabilities

Combinations of these, as well as **age-related** limitations or **temporary** impediments such as glare from the sun or one-handed operation of a device, are also included.

**A11y** is used as an acronym for accessibility and stands for the *11 digits between the "a" and the "y"*. It is pronounced as "A-one-one-Y", "A-eleven-Y" or also freely spoken as "ally". <br>

## Four Principles of WCAG 2 (POUR)
(cited from [WebAIM](https://webaim.org/resources/quickref/), 24.04.22)
- **Perceivable** - Available through sight, hearing, or touch.
- **Operable** - Compatible with keyboard or mouse.
- **Understandable** - Easy to comprehend.
- **Robust** - Works across browsers, assistive technologies, mobile devices, old devices/browsers, etc. Follows standards.

<br>

## My personal recommendation to learn about accessibility at the beginning
- Read the [ADG* Accessibility Developer Guide](https://www.accessibility-developer-guide.com/) to get started <br>
- Use [Lighthouse](https://developers.google.com/web/tools/lighthouse) in Chrome DevTools (read the ADG* for other options)


### Remember
- Use semantic HTML
- ARIA-Rule #1: Don’t use ARIA, use native HTML instead (cited from [deque Blog](https://www.deque.com/blog/top-5-rules-of-aria/#:~:text=Rule%20%231%3A%20Don't,in%20HTML%2C%20then%20use%20ARIA.), 24.04.22)
- Make sure your content is accessible via keyboard


<br>


## WCAG Web Content Accessibility Guidelines: Version History (24.04.22)


|          | Version      | Introduction          | Status         | Comment        |   
| --------------- | ------------ | ------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | 
|                 | WCAG 3.0     | April 2022    | Draft   | [W3C Editor's Draft WCAG 3.0](https://w3c.github.io/silver/guidelines/)                                                                                   |    
|                 | WCAG 3.0     | April 2022    | WIP     | [Silver Taskforce working on WCAG 3.0](https://w3c.github.io/silver/), [WCAG 3.0](https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/) |    
|                 | WCAG 2.2     | May 2021      | Draft   | [W3C Working Draft WCAG 2.2](https://www.w3.org/TR/WCAG22/)                                                                                               |  
| **recommended** | **WCAG 2.1** | **June 2018** | **Current** | **[WCAG 2.1](https://www.w3.org/TR/WCAG21/)**     |
|                 | WCAG 2.0     | December 2008 | Old    |  [WCAG 2.0](https://www.w3.org/TR/WCAG20/)                                                                                                                                                |   
|                 | WCAG 1.0     | May 1999      | Outdated     |  [WCAG 1.0](https://www.w3.org/TR/WAI-WEBCONTENT/) |  


<br><br>


# Resources mentioned in my survey and some more

(Resources with * and comment indicate either that the ressource is not yet in it's final version or that is is quite old.)

## WCAG Web Content Accessibility Guidelines 
- Main page [https://www.w3.org/WAI/](https://www.w3.org/WAI/) 
- Overview [https://www.w3.org/WAI/standards-guidelines/wcag/](https://www.w3.org/WAI/standards-guidelines/wcag/) 
- Quickref [https://www.w3.org/WAI/WCAG21/quickref/](https://www.w3.org/WAI/WCAG21/quickref/)
- Easy Checks – A First Review of Web Accessibility [https://www.w3.org/WAI/test-evaluate/preliminary/](https://www.w3.org/WAI/test-evaluate/preliminary/)
- Tutorials [https://www.w3.org/WAI/tutorials/](https://www.w3.org/WAI/tutorials/)
- Accessibility Statement Generator [https://www.w3.org/WAI/planning/statements/generator/#create](https://www.w3.org/WAI/planning/statements/generator/#create)
- Tools List [https://www.w3.org/WAI/ER/tools/](https://www.w3.org/WAI/ER/tools/)
- WAI-Aria Web Accessibility Initiative – Accessible Rich Internet Applications [https://www.w3.org/TR/wai-aria/](https://www.w3.org/TR/wai-aria/)


## Swiss resources

Big contributors
- [Access for All / Zugang für alle](https://www.access-for-all.ch/ch/)
- Eidgenössische Büro für die Gleichstellung von Menschen mit Behinderungen EBGB: [E-Accessibility](https://www.edi.admin.ch/edi/de/home/fachstellen/ebgb/themen-der-gleichstellung/e-accessibility-.html)

### General Information
- Official: eCH-0059 Schweizer Accessibility Standard [http://ech.ch/de/standards/60476](http://ech.ch/de/standards/60476)
- ADG* Accessibility Developer Guide [https://www.accessibility-developer-guide.com/](https://www.accessibility-developer-guide.com/) 

### Swiss Accessibility-Checklist
- Overview and status of the checklist on the website of [Access for All](https://www.access-for-all.ch/ch/barrierefreiheit/barrierefreies-webdesign/accessibility-checkliste-2-1.html)
- Schweizer Accessibility-Checklist 2.1 (*Vorabversion/Alpha) [https://a11y.digitaldialog.swiss/](https://a11y.digitaldialog.swiss/)  
- Accessibility Checklist 2.0 [https://www.accessibility-checklist.ch/](https://www.accessibility-checklist.ch/) (*Content last updated 19.06.2010) 

## Great international resources about accessibility
- mdn web docs about accessibility [https://developer.mozilla.org/en-US/docs/Web/Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility) 
- German accessibility test tools list / Werkzeugliste der deutschen **B**arrierefreie-**I**nformations**t**echnik-**V**erordnung (BITV) [https://www.bitvtest.de/bitv_test/das_testverfahren_im_detail/werkzeugliste.html](https://www.bitvtest.de/bitv_test/das_testverfahren_im_detail/werkzeugliste.html)
- WebAIM Quickref about Web Accessibility Principles [https://webaim.org/resources/quickref/](https://webaim.org/resources/quickref/) 



<br><br>
___
<br><br>
Last update:<br>
25.02.2025: Giving Mixa & Obsidian combination a try: https://a11y.mixa.site/
02.02.2025: Since GitHub Pages required a subscription and I never got contacted in regards to the repository I previously set the repository to private. I'm opening the repository up again without the GitHub Page. There will be some updates for a new ressources list probably in March/April 2025.

09.08.2022: This site will not be updated since there are already so many other pages about accessibility. For example the website about accessibility of [Oblique (the front-end framework for Swiss branded UI based on Angular)](https://oblique.bit.admin.ch/guidelines/accessibility).<br>

30.08.2022: Added note about everything belonging to the FFHS.

April 2022: For my bachelor thesis I researched resources for developers about accessibility. It's a work in progress until end of August 2022. Afterwards I might update it if I come across something helpful to add. 

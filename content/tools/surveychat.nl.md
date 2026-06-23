---
title: "surveychat"
url: "/nl/surveychat/"
weight: 3
summary: "Voer vragenlijsten en gerandomiseerde experimenten uit met LLM-gestuurde conversationele AI-agents, zonder maatwerk-webappcode."
---

`surveychat` is een open source webapplicatie waarmee onderzoekers vragenlijsten kunnen afnemen en gerandomiseerde experimenten kunnen uitvoeren met conversationele agents op basis van large language models (LLM's), zonder dat zij maatwerk-webappcode hoeven te ontwikkelen. Het systeem ondersteunt twee primaire modi: (i) **survey mode**, waarin alle deelnemers met dezelfde chatbotconfiguratie interacteren, en (ii) **experiment mode**, waarin deelnemers willekeurig worden toegewezen aan een van meerdere chatbotcondities, elk gedefinieerd door een door de onderzoeker opgegeven persona en taalmodel. Na afloop van de interactie ontvangen deelnemers een geanonimiseerd JSON-transcript dat alleen de rol, inhoud en tijdstempel van elk bericht bevat. Dit transcript kan worden teruggekopieerd naar het bovenliggende vragenlijstplatform (zoals Qualtrics), waarin de chatbotinterface zelf ook direct kan worden ingesloten. De frontend van `surveychat` is gebouwd met Streamlit, en de volledige applicatie wordt geconfigureerd via een enkel Python-bestand. Het systeem slaat geen gespreksdata op de server op en is compatibel met elke chat-completions-compatibele API-endpoint - inclusief lokaal gehoste modellen - waardoor onderzoekers volledige controle behouden over modelkeuze, API-gebruik, datajurisdictie en naleving van ethische en regelgevende vereisten.

Meer informatie op [surveychat.github.io](https://surveychat.github.io/).

**[Bekijk code op GitHub](https://github.com/surveychat/surveychat)**

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/surveychat/surveychat/main/paper/surveychat-interface-2.png" alt="Chatinterface" style="max-width:100%;" />
      <br/><em>Deelnemers chatten met het AI-model</em>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/surveychat/surveychat/main/paper/surveychat-interface-3.png" alt="Transcript export" style="max-width:100%;" />
      <br/><em>Aan het einde kopieren zij hun transcript terug naar je vragenlijst (bijv. Qualtrics)</em>
    </td>
  </tr>
</table>

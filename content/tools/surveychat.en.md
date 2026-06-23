---
title: "surveychat"
url: "/surveychat/"
weight: 3
summary: "Administer surveys and randomized experiments with LLM-based conversational agents without custom web application code."
---

`surveychat` is an open-source web application that enables researchers to administer surveys and conduct randomized experiments involving large language model (LLM)-based conversational agents, without the need to develop custom web application code. The system supports two primary operational modes: (i) **survey mode**, in which all participants interact with an identical chatbot configuration, and (ii) **experiment mode**, in which participants are randomly assigned to one of multiple chatbot conditions, each defined by a researcher-specified persona and language model. Upon completion of the interaction, participants receive an anonymized JSON transcript that contains only the role, content, and timestamp of each message. This transcript can be copied back into the parent survey platform (such as Qualtrics), within which the chatbot interface itself can also be directly embedded. The frontend of `surveychat` is implemented using Streamlit, and the entire application is configured via a single Python file. The system does not persist conversation data on its server and is compatible with any chat-completions-compatible API endpoint - including locally hosted models - thereby allowing researchers to retain full control over model selection, API usage, data jurisdiction, and adherence to ethical and regulatory requirements.

Learn more at [surveychat.github.io](https://surveychat.github.io/).

**[View code on GitHub](https://github.com/surveychat/surveychat)**

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/surveychat/surveychat/main/paper/surveychat-interface-2.png" alt="Chat interface" style="max-width:100%;" />
      <br/><em>Participants chat with the AI model</em>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/surveychat/surveychat/main/paper/surveychat-interface-3.png" alt="Transcript export" style="max-width:100%;" />
      <br/><em>At the end, they copy their transcript back into your survey (e.g. Qualtrics)</em>
    </td>
  </tr>
</table>

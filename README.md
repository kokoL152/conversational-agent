# English Conversational Agent

We reversed the normal Learning Scene by changing the conversation iniative to user.

From the teacher/agent asks, learners answer, to learners ask, agent answers.

We set the scene like the learner is a service provider at the information desk,
the agent is the customer that need help.

The goal for the learner is to a)initiate the conversation; b)undersatand the need of the customer; c)come up a plan to help the customer

![image](https://github.com/kokoL152/conversational-agent/assets/147573258/7cef0ffb-94c1-4222-b81e-16eb84fe5011)

_Fig.1 System interface_

## Steps:

1. Users press the Activate button to iniatiate the conversation

2. system will keep track of the speech by speech to text(supported by Oculus SDK Speech to Text)
   
3. When the recognition finish, the recognition result on the left bottom side, will change to white from grey

![image](https://github.com/kokoL152/conversational-agent/assets/147573258/6d431f26-2a36-4617-8e24-a7ada2ed32ef)

4. System will distinguish the speech by analyzing the intent by Natural Language Processing
   
5. NLP, content training, reply setting module were supported by [Wit.ai](https://wit.ai/)

![image](https://github.com/kokoL152/conversational-agent/assets/147573258/fefff8e6-945c-4349-a9ad-4714b28f8551)

_Fig.2 Content training in Wit.ai_

![image](https://github.com/kokoL152/conversational-agent/assets/147573258/69cae0a0-d310-4b4a-b663-85448dc28c13)

_Fig.3 Conversation logic building in wit.ai_


![image](https://github.com/kokoL152/conversational-agent/assets/147573258/3e7bf397-d1c0-42b0-a25a-115dcfdacc17)

_Fig.4 The test conversation on wit.ai_
blue side is the learner, grey side is the reply from wit.ai

6. The reply message output from Wit.ai will be returned to Unity

7. Oculus SDK will support the text to speech, and convert it into real-time voice feedback to the learner.

References:
1. Wit.ai: https://wit.ai/
2. OculusSDK: https://developer.oculus.com/downloads/package/oculus-voice-sdk/
3. Agent Avatar: hand made by vroid(https://vroid.com/)

   

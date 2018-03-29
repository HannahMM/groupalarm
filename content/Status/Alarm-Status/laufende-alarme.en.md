+++
title = "Current alerts"
weight = 1
+++

If an alert was triggered, the “Alert feedback” screen appears. All
recipients to whom an alert was sent, are included in the feedback list.
Follow the alert process in real-time here.

The participant responses can be viewed immediately at the feedback view
and are updated on an ongoing basis. The dialogue window (“red box”)
displays a graphical overview of the analysed acknowledgements. This
overview shows the amount of participants with a specific status.
Positive, negative and invalid acknowledgements are included in the
list.
![](/img/alert_feedback_en.0b99be6c31ac76617452935af1b85ca2.png?width=700&classes=shadow)
Alerted stuff must acknowledge the alert with the predefined syntax so
that the answers can be analysed. The syntax stipulates that an
acknowledgement must start with one of the two keywords “Ja” or “Nein”,
“OK” or “NOK” or “Oui”/“Non”, “Si”/“No”, “Yes”/“No”. If an additional
text is sent, it must be separated from the keyword with a *space* (a
comma or a full stop after the keyword cannot be evaluated).

  -------------------------------- ----------------------
  YES                              NO
  Yes I will be there in 20 min.   No I won\`t make it
  Yes I\`ll be there               No I won\`t make it
  OK                               NOK
  OK I will be there in 20 min     NOK I won\`t make it
  OK I\`ll be there                NOK I can\`t come
  -------------------------------- ----------------------

Example of *invalid* answers:

- It's OK, I'll be there (incorrect keyword)

- Yes, in 15 min. (keyword separated by comma)

    

If eAlarm emergency cannot evaluate the responses due to incorrect
syntax, the feedback recipient is assigned the status “Invalid” and the
entire answer SMS is shown in the result column.
![](/img/feedback_negativ_neu_en.png)
The feedback recipient can manually set the “Result” to “Yes” or “No”
based on the text by selecting the green tick
![](/img/gutzeichengruen_en.png)
or the red cross
![](/img/xrot_en.png)
. If the recipient manually sets the participant to “Yes” for example,
he is displayed in eAlarm as follows.
![](/img/manuelgesetzt_en.png)
The original text in the result is overwritten with the information on
the manual status change.

The alert feedback uses a bar diagram to show the progress of
participant acknowledgement. You can see at a glance the relative
percentage of recipients who have given a positive or negative answer
and the number of participants that have not yet acknowledged the alert.

The list of alert details shows when the alert was scheduled and
started, as well as for how long the alert has been running. The traffic
light indicates when the limit of the successful alert has been reached.
When the traffic light switches from red to orange, a predefined number
of participants have already acknowledged the alert positively. If the
traffic light switches to green, the predefined number of positive
answers required in the registry has been reached and you can end the
alert.

Once the eAlarm emergency session has come to an end, you must log out
of the application. Log out by clicking **Logout** on the tab “Session”
tab.

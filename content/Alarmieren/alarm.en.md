+++
title = "Alert creation"
weight = 1
+++

### Table of Contents 

- [Alert creation](#alert_creation)

- [General](#general)

- [Units](#units)

- [Text](#text)

- [Coordinates](#coordinates)

- [Alert options](#alert_options)

- [Schedule](#schedule)

<a name="alert_creation"></a>
### Alert creation 

The input screen *“Create alert”* opens, once a participant a group or
root is chosen and the button **“Alert”** is clicked.

**General:** See the alert name and an optional description of the
current alert.

**Units:** See the amount of subscribers within the amount of units that
are planned for the alert.

**Text:** Enter a new free text in *“Free text”* before subsequently
enabling it (clicking the *“Send Alert”* button). If predefined text was
created, optionally use this as alert text by clicking ![](/img/runderblauesdings.png?classes=shadow)
or with *“QuickEdit”*. Texts from “Previous alerts” can be incorporated
into the free text and reused with *“QuickEdit”*.

**Coordinates:** Define, if you want to include coordinates in the alert
message.

**Alert options:** Define other settings for alert media, termination
criteria, info transmission, etc. here.

**Schedule:** Define, whether the alert should be sent immediately or
scheduled for a future date.

If all required settings are done, the alert can be triggered by
pressing the “**Send Alert**” button (button switched to red).

In addition to the alert trigger option directly from the GUI, **eAlarm
emergency** also supports several remote triggers. Trigger the alert by
SMS, call+ DTMF menu, direct dial and via a web link. Find more details
about triggering alerts remotely in handout: “eAlarm emergency remote
triggering”.

(coming soon…)

![](/img/alarm_erstellen_freitext_en.34542f25cb3bf6b54af64377f65e68e4.png?classes=shadow)

<a name="general"></a>
### General 

![](/img/ealarm_erstellen_allgemein_en.png?classes=shadow)
Changing the **“Alert name”**. Describe the alert in **“Description”**
(optional). The alert creator is shown in **“Creator”**. The alert
creation date can be found in **“Date/time”**.

<a name="units"></a>
### Units 

![](/img/alarm_erstellen_einheit_en.072081be3fe2f6fff7012d0fd8c8bc3f.png?classes=shadow)

See how many participants have been selected for the alert and being
assigned to which units in **“Unit”**. Duplicate participants and such
participants which cannot be alerted are not shown. Other
units/participants can be added under *\[edit\].*

<a name="text"></a>
### Text 

![](/img/alarm_erstellen_text_en.de7d3eeb6846176eeb25a2118fd8cd9b.png)
Before triggering the alert, it is possible to determine whether you
want to select the predefined text (by clicking
![](/img/runderblauesdings.png?classes=shadow))
or create a new
![](/img/freitext_en.png?classes=shadow)
free text at this time. A predefined text can be incorporated and
changed by clicking *“QuickEdit”.* In advantage, the dispatcher does not
have to re-enter the entire text in *“QuickEdit”* but is able to use
predefined text that can be changed to its needs.

<a name="coordinates"></a>
### Coordinates 

Decide in the “Transmit coordinates” section, whether coordinates shall
be transmitted or
not.![](/img/koordinaten_yes_no.png?classes=shadow)

Enter the required address in “Address details”.

![](/img/koordinaten_1.png?classes=shadow)

Alternatively, enter the coordinates here:

![](/img/koordinaten_2.png?classes=shadow)

Once an address was entered, it will be automatically converted into the
WGS84 format.

![](/img/koordinaten_3.a70bc0475016d483158f82c1ad7c3d8a.png?classes=shadow)

<a name="alert_options"></a>
### Alert options 

![](/img/alarm_erstellen_alarmoptionen_en.edc077dabe6c246ea46ee6a2e5ed68c8.png?classes=shadow)

**“Alert the following media”:** Decide which resource has to be alerted
and which not.

**“SMSprio”:** Specify whether the alert should be sent over “SMSprio”
or not. If **“NO”** is selected, the Flash SMS will not be sent.
**“Weekly planner”:** (available in Media Priority List Plus module
only)

- From participant data: the participants are alerted based on the
    predefined weekly planner

- Test (default): the predefined weekly planner (optional module) is
    not used for this option.

**“Cancel”:** Specify criteria to automatically terminate an alert here.
Once one of the defined termination criteria is achieved during the
alert process, the alert is being terminated.

- Termination due to x% of participants sending a positive
    acknowledgement 

- Termination due to x participants sending a positive acknowledgement

- Termination x minutes after the alert was triggered

**“Info transmission”:** Define the people who should receive a specific
document by e-mail/fax. In this section, it is also defineable which
e-mail address, fax and/or mobile number is used for sending a regular
summary about the alert status.

**Comment:** Regular summaries regarding an ongoing alert can also be
sent.

<a name="schedule"></a>
### Schedule 

![](/img/alarm_erstellen_versandstatistik_en.b25eacbba3534406a4ca854153036b94.png?classes=shadow)

**eAlarm** is generally configured for an alert to be triggered
directly. You can also schedule an alert to be triggered under
scheduling options (“Send at this date”) by defining which day and at
what time the alert should be triggered. For instance, these kinds of
“scheduled” alerts can be used for test alerts, as they can be planned
relatively easily in advance. Scheduled alerts can be viewed and deleted
in the “Status” menu.


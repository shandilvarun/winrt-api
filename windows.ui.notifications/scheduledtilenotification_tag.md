---
-api-id: P:Windows.UI.Notifications.ScheduledTileNotification.Tag
-api-type: winrt property
---

<!-- Property syntax
public string Tag { get;  set; }
-->

# Windows.UI.Notifications.ScheduledTileNotification.Tag

## -description
Gets or sets a string that Windows can use to prevent duplicate notification content from appearing in the queue.

## -property-value
A string of 16 characters or less (plus a terminating null character) that identifies the notification in the stack. While there is no set form for the string content, we recommend that it should relate to the content of the notification.

## -remarks
[ScheduledTileNotification.tag](scheduledtilenotification_tag.md) and [ScheduledTileNotification.id](scheduledtilenotification_id.md) serve similar purposes: 
+ The [ScheduledTileNotification.tag](scheduledtilenotification_tag.md) property is used by Windows to prevent duplicate notification content from appearing in the queue at the same time. It allows the notification to be updated in-place in the queue to prevent it from containing out-of-date information.
+ The [ScheduledTileNotification.id](scheduledtilenotification_id.md) property identifies the notification in the schedule. This allows the notification to be identified or removed from the schedule.
<!-- @WRITER erictill 12/14/2011 : TBD-Question I have my doubts that this is right. -->


## -examples

## -see-also
[Scheduled notifications sample](http://go.microsoft.com/fwlink/p/?linkid=241614), [Guidelines and checklist for scheduled notifications](http://msdn.microsoft.com/library/ca9e9121-d1b1-461f-9c7e-b25225d917ca)
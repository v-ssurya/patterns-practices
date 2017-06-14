---
TOCTitle: 'PubSubEvent(TPayload) Methods'
Title: 'PubSubEvent(TPayload) Methods (Microsoft.Practices.Prism.PubSubEvents)'
ms:assetid: 'Methods.T:Microsoft.Practices.Prism.PubSubEvents.PubSubEvent\`1'
ms:mtpsurl: 'pubsubevent-tpayload-methods-mspp-pubsubevents.md'
---


# PubSubEvent(Of TPayload) Methods

The [PubSubEvent(Of TPayload)](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents) type exposes the following members.

## Methods

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Contains(Action&lt;TPayload&gt;)](/patterns-practices/reference/mspp-mvvm-namespace.pubsubevent%601.contains(system.action%7b%600%7d))</td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Contains(SubscriptionToken)](/patterns-practices/reference/mspp-mvvm-namespace.eventbase.contains(microsoft.practices.prism.pubsubevents.subscriptiontoken))</td>
<td><div class="summary">
Returns trueTruetruetrue (True in Visual Basic) if there is a subscriber matching [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken).
</div>
(Inherited from [EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current <a href="http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/dfwy45w9)</td>
<td><div class="summary">
Gets the [Type](http://msdn.microsoft.com/en-us/library/42892f65) of the current instance.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InternalPublish](/patterns-practices/reference/mspp-mvvm-namespace.eventbase.internalpublish(system.object%5b%5d))</td>
<td><div class="summary">
Calls all the execution strategies exposed by the list of [IEventSubscription](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription).
</div>
(Inherited from [EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[InternalSubscribe](/patterns-practices/reference/mspp-mvvm-namespace.eventbase.internalsubscribe(microsoft.practices.prism.pubsubevents.ieventsubscription))</td>
<td><div class="summary">
Adds the specified [IEventSubscription](/patterns-practices/reference/mspp-mvvm-namespace.ieventsubscription) to the subscribers' collection.
</div>
(Inherited from [EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Publish](https://msdn.microsoft.com/en-us/library/dn683930(v=pandp.50))</td>
<td><div class="summary">
Publishes the [PubSubEvent&lt;TPayload&gt;](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents).
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;)](https://msdn.microsoft.com/en-us/library/dn683969(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the [PublisherThread](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.threadoption). [PubSubEvent&lt;(Of &lt;(TPayload&gt;)&gt;)](https://msdn.microsoft.com/library/microsoft.practices.prism.pubsubevents.pubsubevent%601) will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the target of the supplied action delegate.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption)](https://msdn.microsoft.com/en-us/library/dn736155(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event. PubSubEvent will maintain a [WeakReference](http://msdn.microsoft.com/en-us/library/hbh8w2zd) to the Target of the supplied action delegate.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, Boolean)](https://msdn.microsoft.com/en-us/library/dn683949(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event that will be published on the [PublisherThread](/patterns-practices/reference/mspp-mvvm-namespace.threadoption).
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean)](https://msdn.microsoft.com/en-us/library/dn683942(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Subscribe(Action&lt;TPayload&gt;, ThreadOption, Boolean, Predicate&lt;TPayload&gt;)](https://msdn.microsoft.com/en-us/library/dn736225(v=pandp.50))</td>
<td><div class="summary">
Subscribes a delegate to an event.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/7bxwbwt2)</td>
<td><div class="summary">
Returns a string that represents the current object.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Unsubscribe(Action&lt;TPayload&gt;)](https://msdn.microsoft.com/en-us/library/dn736235(v=pandp.50))</td>
<td><div class="summary">
Removes the first subscriber matching [Action&lt;T&gt;](http://msdn.microsoft.com/en-us/library/018hxwa8) from the subscribers' list.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Unsubscribe(SubscriptionToken)](/patterns-practices/reference/mspp-mvvm-namespace.eventbase.unsubscribe(microsoft.practices.prism.pubsubevents.subscriptiontoken))</td>
<td><div class="summary">
Removes the subscriber matching the [SubscriptionToken](/patterns-practices/reference/mspp-mvvm-namespace.subscriptiontoken).
</div>
(Inherited from [EventBase](/patterns-practices/reference/mspp-mvvm-namespace.eventbase).)</td>
</tr>
</tbody>
</table>

## See Also

[PubSubEvent(Of TPayload) Class](/patterns-practices/reference/pubsubevent-tpayload-class-mspp-pubsubevents)<br/>
[Microsoft.Practices.Prism.PubSubEvents Namespace](/patterns-practices/reference/mspp-pubsubevents-namespace)
研究对象SignalEmitter
1.SignalEmitter是如何发送时间的？
TimeNotificationBehaviour（PlayableBehaviour）会每帧调用PrepareFrame触发TriggerNotificationsInRange(m_PreviousTime, currentTime, info, playable, true);

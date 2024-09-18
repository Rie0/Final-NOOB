
# NOOB SYSTEM

---
"Noob" is a comprehensive platform designed to revolutionize the world of gaming tournaments and eSports management. This website offers a centralized hub for organizing tournaments, adding coaching sessions, and offering academy courses for gamers of all levels.
Key features of "Noob" include:
Tournament Management: Effortlessly create, manage, and finalize gaming tournaments. The platform supports dynamic participant management, real-time match tracking, and seamless communication with organizers.
Coaching and Training: Players can access a variety of coaching sessions and academy courses tailored to different games and skill levels. This helps them to improve their gameplay, strategize better, and advance their competitive edge.
Team Registration and Scouting: "Noob" enables the registration of gaming teams and scouting of individual players, fostering a competitive community and helping organizations find new talent.
Vendor and PC Center Integration: Vendors can list PC centers on the platform, allowing players to find and subscribe to local or preferred gaming centers. This creates a bridge between gamers and gaming venues, enhancing community engagement.
Subscription Management: Players can easily subscribe to their chosen PC centers, benefiting from exclusive deals, updates, and events, while PC centers manage their subscriptions and user interactions smoothly.
"Noob" aims to bring together gamers, teams, coaches, and gaming centers in a unified platform, enhancing the gaming experience and fostering a vibrant eSports community.
---

"نوب" هو منصة شاملة تهدف إلى إحداث ثورة في عالم البطولات الرياضية الإلكترونية وإدارة الألعاب. يقدم هذا الموقع مركزًا موحدًا لتنظيم البطولات، وإضافة جلسات تدريبية، وتقديم دورات أكاديمية للاعبين من جميع المستويات.
تشمل الميزات الرئيسية لموقع "نوب":
إدارة البطولات: إنشاء البطولات الرياضية الإلكترونية وإدارتها وإتمامها بكل سهولة. تدعم المنصة إدارة المشاركين بشكل ديناميكي، وتتبع المباريات في الوقت الحقيقي، والتواصل السلس مع المنظمين.
التدريب والتطوير: يمكن للاعبين الوصول إلى مجموعة متنوعة من جلسات التدريب والدورات الأكاديمية المخصصة لألعاب ومستويات مهارات مختلفة. يساعدهم ذلك على تحسين مهاراتهم، وتطوير استراتيجيات أفضل، وتعزيز قدراتهم التنافسية.
تسجيل الفرق واستكشاف اللاعبين: يتيح "نوب" تسجيل الفرق الرياضية الإلكترونية واستكشاف اللاعبين الفرديين، مما يعزز من تكوين مجتمع تنافسي ويساعد المنظمات على اكتشاف المواهب الجديدة.
دمج الموردين ومراكز الكمبيوتر: يمكن للموردين إدراج مراكز الكمبيوتر على المنصة، مما يسمح للاعبين بالبحث عن مراكز ألعاب محلية أو مفضلة والاشتراك فيها، مما يعزز من تفاعل المجتمع.
إدارة الاشتراكات: يمكن للاعبين الاشتراك بسهولة في مراكز الكمبيوتر المختارة، والاستفادة من العروض الحصرية، والتحديثات، والفعاليات، بينما تدير مراكز الكمبيوتر اشتراكاتها وتفاعلات المستخدمين بسلاسة.
يهدف "نوب" إلى جمع اللاعبين، والفرق، والمدربين، ومراكز الألعاب في منصة واحدة، مما يعزز تجربة الألعاب ويدعم مجتمع الرياضات الإلكترونية النابض بالحياة.



## Links

- [Figma Design](https://www.figma.com/design/uGFtV8Jcs5FD52LDU8ESxv/Untitled?node-id=0-1&t=V7eJ7Z3AifS0XrJO-1)
- [Presentation](https://www.canva.com/design/DAGQ_9lAwuU/uPJlkOj0XV8sx3AN4qdTiA/edit?utm_content=DAGQ_9lAwuU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Postman Documentation](https://documenter.getpostman.com/view/30968689/2sAXqqdNjT)

---

## Diagrams
- [Usecase diagram P1](https://lucid.app/lucidchart/56ca0f5c-4eb7-4e79-b0f6-14d190e348cf/edit?view_items=cnq~SSIeWqfB&invitationId=inv_1829aead-4e3d-4d87-a7c0-3da38e9f117b)
- [Usecase diagram P2](https://lucid.app/lucidchart/e5455375-88e3-4ebc-93fe-774c0053ca63/edit?beaconFlowId=8798B8329F0DF94E&invitationId=inv_7373ffb9-81f0-4ab2-ac23-4628433424ca&page=0_0#)
- [Class diagram](https://drive.google.com/file/d/1bruFimOwVR5KivpLjTzH2Wah70n8tbzL/view)


## My endpoints

#### getLeague

```http
 /api/v1/league/get/{leagueId}
```

#### getAllParticipants

```http
 /api/v1/league/{leagueId}/get-all-participants
```

#### participateInLeague

```http
 /api/v1/league/{leagueId}/participate
```

#### withdrawFromLeague

```http
 /api/v1/league/{leagueId}/withdraw
```

#### kickParticipant

```http
 /api/v1/league/{leagueId}/kick-participant/{playerId}
```

#### changeLeagueDates

```http
 /api/v1/league/{leagueId}/change-dates
```
#### setLeagueRoundDate

```http
 /api/v1/league/{leagueId}/round/{roundId}/set-dates
```

#### setLeagueMatchDate

```http
 /api/v1/league/{leagueId}/match/{matchId}/set-dates
```
#### setLeagueToReady

```http
 /api/v1/league/{leagueId}/set-ready
```

#### startMatch

```http
 /api/v1/league/{leagueId}/match/{matchId}/start-match
```

#### add1toParticipant1Score

```http
 api/v1/{leagueId}/match/{matchId}/add-1score-to-participant1
```

#### add1toParticipant2Score

```http
 api/v1/{leagueId}/match/{matchId}/add-1score-to-participant2
```

#### sub1fromParticipant1Score

```http
 api/v1/{leagueId}/match/{matchId}/sub-1score-from-participant1
```

#### sub1fromParticipant2Score

```http
 api/v1/{leagueId}/match/{matchId}/sub-1score-from-participant2
```

#### finishMatch

```http
 api/v1/{leagueId}/match/{matchId}/finish-match
```

#### cancelMatch

```http
 api/v1/{leagueId}/match/{matchId}/cancel-match
```

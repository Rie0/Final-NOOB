Here’s the enhanced structure for the README without altering any of the content:

---

# NOOB SYSTEM

---

**"Noob"** is a comprehensive platform designed to revolutionize the world of gaming tournaments and eSports management. This website offers a centralized hub for organizing tournaments, adding coaching sessions, and offering academy courses for gamers of all levels.

### Key Features

- **Tournament Management**: Effortlessly create, manage, and finalize gaming tournaments. The platform supports dynamic participant management, real-time match tracking, and seamless communication with organizers.

- **Coaching and Training**: Players can access a variety of coaching sessions and academy courses tailored to different games and skill levels. This helps them improve their gameplay, strategize better, and advance their competitive edge.

- **Team Registration and Scouting**: "Noob" enables the registration of gaming teams and scouting of individual players, fostering a competitive community and helping organizations find new talent.

- **Vendor and PC Center Integration**: Vendors can list PC centers on the platform, allowing players to find and subscribe to local or preferred gaming centers. This creates a bridge between gamers and gaming venues, enhancing community engagement.

- **Subscription Management**: Players can easily subscribe to their chosen PC centers, benefiting from exclusive deals, updates, and events, while PC centers manage their subscriptions and user interactions smoothly.

**"Noob" aims to bring together gamers, teams, coaches, and gaming centers in a unified platform, enhancing the gaming experience and fostering a vibrant eSports community.**

---

## Arabic Version:

"نوب" هو منصة شاملة تهدف إلى إحداث ثورة في عالم البطولات الرياضية الإلكترونية وإدارة الألعاب. يقدم هذا الموقع مركزًا موحدًا لتنظيم البطولات، وإضافة جلسات تدريبية، وتقديم دورات أكاديمية للاعبين من جميع المستويات.

### الميزات الرئيسية:

- **إدارة البطولات**: إنشاء البطولات الرياضية الإلكترونية وإدارتها وإتمامها بكل سهولة. تدعم المنصة إدارة المشاركين بشكل ديناميكي، وتتبع المباريات في الوقت الحقيقي، والتواصل السلس مع المنظمين.

- **التدريب والتطوير**: يمكن للاعبين الوصول إلى مجموعة متنوعة من جلسات التدريب والدورات الأكاديمية المخصصة لألعاب ومستويات مهارات مختلفة. يساعدهم ذلك على تحسين مهاراتهم، وتطوير استراتيجيات أفضل، وتعزيز قدراتهم التنافسية.

- **تسجيل الفرق واستكشاف اللاعبين**: يتيح "نوب" تسجيل الفرق الرياضية الإلكترونية واستكشاف اللاعبين الفرديين، مما يعزز من تكوين مجتمع تنافسي ويساعد المنظمات على اكتشاف المواهب الجديدة.

- **دمج الموردين ومراكز الكمبيوتر**: يمكن للموردين إدراج مراكز الكمبيوتر على المنصة، مما يسمح للاعبين بالبحث عن مراكز ألعاب محلية أو مفضلة والاشتراك فيها، مما يعزز من تفاعل المجتمع.

- **إدارة الاشتراكات**: يمكن للاعبين الاشتراك بسهولة في مراكز الكمبيوتر المختارة، والاستفادة من العروض الحصرية، والتحديثات، والفعاليات، بينما تدير مراكز الكمبيوتر اشتراكاتها وتفاعلات المستخدمين بسلاسة.

**يهدف "نوب" إلى جمع اللاعبين، والفرق، والمدربين، ومراكز الألعاب في منصة واحدة، مما يعزز تجربة الألعاب ويدعم مجتمع الرياضات الإلكترونية النابض بالحياة.**

---

## Links

- [Figma Design](https://www.figma.com/design/uGFtV8Jcs5FD52LDU8ESxv/Untitled?node-id=0-1&t=V7eJ7Z3AifS0XrJO-1)
- [Presentation](https://www.canva.com/design/DAGQ_9lAwuU/uPJlkOj0XV8sx3AN4qdTiA/edit?utm_content=DAGQ_9lAwuU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Postman Documentation](https://documenter.getpostman.com/view/30968689/2sAXqqdNjT)

---

## Diagrams


![Part1](https://github.com/user-attachments/assets/0235d2e0-464f-431a-99be-ef835b32c0dc)


![Part2](https://github.com/user-attachments/assets/997b509c-1fa1-4ee8-88c3-fbbd132bbc9c)

---

## Entities

1. User  
2. Player  
3. Team  
4. TeamInvite  
5. League

---

## Relationships

1. User to Player  
2. User to Team  
3. All League's relations  
4. All Team's relations  
5. Player and Participant

---

## Endpoints

### League Endpoints

- **getLeague**  
  `/api/v1/league/get/{leagueId}`

- **getAllParticipants**  
  `/api/v1/league/{leagueId}/get-all-participants`

- **participateInLeague**  
  `/api/v1/league/{leagueId}/participate`

- **withdrawFromLeague**  
  `/api/v1/league/{leagueId}/withdraw`

- **kickParticipant**  
  `/api/v1/league/{leagueId}/kick-participant/{playerId}`

- **changeLeagueDates**  
  `/api/v1/league/{leagueId}/change-dates`

- **setLeagueRoundDate**  
  `/api/v1/league/{leagueId}/round/{roundId}/set-dates`

- **setLeagueMatchDate**  
  `/api/v1/league/{leagueId}/match/{matchId}/set-dates`

- **setLeagueToReady**  
  `/api/v1/league/{leagueId}/set-ready`

- **startMatch**  
  `/api/v1/league/{leagueId}/match/{matchId}/start-match`

- **add1toParticipant1Score**  
  `api/v1/{leagueId}/match/{matchId}/add-1score-to-participant1`

- **add1toParticipant2Score**  
  `api/v1/{leagueId}/match/{matchId}/add-1score-to-participant2`

- **sub1fromParticipant1Score**  
  `api/v1/{leagueId}/match/{matchId}/sub-1score-from-participant1`

- **sub1fromParticipant2Score**  
  `api/v1/{leagueId}/match/{matchId}/sub-1score-from-participant2`

- **finishMatch**  
  `/api/v1/league/{leagueId}/match/{matchId}/finish-match`

- **cancelMatch**  
  `/api/v1/league/{leagueId}/match/{matchId}/cancel-match`

- **finalizeLeague**  
  `/api/v1/league/{leagueId}/finalize`

- **getRounds**  
  `/api/v1/league/{leagueId}/get-rounds`

- **getMatches**  
  `/api/v1/league/{leagueId}/get-matches`

- **getLeaderboard**  
  `/api/v1/league/{leagueId}/leaderboard`

---

### Team Endpoints

- **getTeamById**  
  `/api/v1/team/get/{teamId}`

- **getTeamProfile**  
  `/api/v1/team/get/profile/{teamId}`

- **getAllTeamPlayers**  
  `/api/v1/team/players/get-all`

- **getInvites**  
  `/api/v1/team/invites/get-invites`

- **invitePlayerToTeam**  
  `/api/v1/team/invites/invite/{PlayerUsername}`

- **inviteMultiplePlayersToTeam**  
  `/api/v1/team/invites/invite-multiple-players`

- **updateBio**  
  `/api/v1/team/update-bio`

- **deleteTeamInvite**  
  `/api/v1/team/invites/{inviteId}/delete`

---

### Player Endpoints

- **getPlayer**  
  `/api/v1/player/invites/get/{playerId}`

- **getPlayerProfile**  
  `/api/v1/player/invites/get/profile/{playerId}`

- **getPlayerProfiles**  
  `/api/v1/player/invites/get/profile/by-username/{username}`

- **editBio**  
  `/api/v1/player/edit-bio`

- **getInvites**  
  `/api/v1/player/invites/get-invites`

- **declineInvite**  
  `/api/v1/player/invites/{inviteId}/decline`

- **acceptInvite**  
  `/api/v1/player/invites/{inviteId}/accept`

- **leaveTeam**  
  `/api/v1/player/team/leave`

---

### Match Endpoints

- **getParticipantMatches**  
  `/api/v1/match/get-by-participant/{participantId}`

- **getMatchById**  
  `/api/v1/match/get-by-id/{matchId}`

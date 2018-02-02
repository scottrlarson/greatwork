# Distributed / Decentralized Social Platforms That Replace Twitter's and Facebook's Centralization of Content

## Diaspora

- [Wikipedia Page](https://en.wikipedia.org/wiki/Diaspora_%28social_network%29)
- [Foundation Website](https://diasporafoundation.org/)
- [Codebase](https://github.com/diaspora/)
- [Activity](https://diapod.net/active/)
- [Federation Info](https://the-federation.info/)

Diaspora's Key Philsophies

**Decentralization**

Instead of everyone’s data being held on huge central servers owned by a large organization, diaspora* exists on independently run servers (“pods”) all over the world. You choose which pod to register with, and you can then connect seamlessly with the diaspora* community worldwide.

**Freedom**

You can be whoever you want to be in diaspora*. Unlike some networks, you don’t have to use your real identity. You can interact with people in whatever way you choose. The only limit is your imagination. diaspora* is also Free Software, giving you liberty over how you use it.

**Privacy**

In diaspora* you own your data. You don’t sign over rights to a corporation or other interest who could use it. In addition, you choose who sees what you share, using Aspects. With diaspora*, your friends, your habits, and your content is your business ... not ours!

| Feature | Option |
|----------:|:---|
| **Active Dev**	| Yes |
| **Mobile App** 	| No |
| **Usability** 	| Good |
| **User Options**	| Lacking |
| **Uptime** 	| Pod Dependent |
| **Cultural Saturation** | European |
| **Bugs** 		| Few |
| **Platform** 	| Social Networking |
| **Platform Type** | blogging/disussions |
| **Network Type**	| Federated |
| **Similarity** 	| Twitter |
| **Content Migration** | No |

### POD Details

One of the greatest freedoms Diaspora offers you is the freedom to choose where your personal data is stored, by choosing a pod. Each pod has a different domain name, and is managed by different people on different servers in different physical locations. You're probably used to having no choice over where your data are stored when you sign up to a new social network, so it's likely you've never had to think about this before. Don't worry -- all pods connect to the same Diaspora network, and once you sign up you'll be communicating and sharing with users across all pods, not just users in your own pod. It's really just a question of where the content you share will be physically hosted, as a security and privacy concern. 

- You can find a pod by checking the [Federation Info](https://the-federation.info/).
- Pod's sometimes close Sign-ups for various reasons, I believe its due to load.
- User saturation is dependent on the particular pod you join, but the pods are all joined together though the federated network. This matters if you just wanted to socialize with people on just a local pod, or you want to socialize with everyone on the federated network.

### My Comments

Diaspora seems pretty well designed in its current form, its very similar to twitter in that you create a profile, and chose what kind of information to share on your profile.

Where Diaspora differs is how content is displayed on your stream (Like a timeline). The main way you populate your stream is you choose a list of hashtags that get saved. Then when you update the page your stream gets populated with content based on those hashtags. So if someone includes #Decentralization in their conversation (Similar to a tweet) then that conversation will be added to your stream along with the comments that were in that conversation. There also does not seem to be a character limit in the conversations you post.

Another cool thing is that you can create categories called [aspects](https://diasporafoundation.org/getting_started/aspects) for your conversations you post, or people you meet to slot into certain categories. This allows each user to filter content into particular aspects. Only people who are part of that aspect see the conversations posted to that aspect. This way you can post conversations that are public to public aspect, or to a private aspect you created. I also use it to post content that I want to look at myself that has no person attached to it. The only problem I see with this is that it seems to save the last aspect(s) you selected and if you forget to change that status you might accidentally post a conversation to the wrong aspect. 

## Mastodon

Mastodon is a free, open-source social network server based on open web protocols like ActivityPub and OStatus. The social focus of the project is a viable decentralized alternative to commercial social media silos that returns the control of the content distribution channels to the people. The technical focus of the project is a good user interface, a clean REST API for 3rd party apps and robust anti-abuse tools.

### Features

**No vendor lock-in: Fully interoperable with any conforming platform**

It doesn't have to be Mastodon, whatever implements ActivityPub or OStatus is part of the social network!

**Real-time timeline updates**

See the updates of people you're following appear in real-time in the UI via WebSockets. There's a firehose view as well!

**Federated thread resolving**

If someone you follow replies to a user unknown to the server, the server fetches the full thread so you can view it without leaving the UI

**Media attachments like images and short videos**

Upload and view images and WebM/MP4 videos attached to the updates. Videos with no audio track are treated like GIFs; normal videos are looped - like vines!

**OAuth2 and a straightforward REST API**

Mastodon acts as an OAuth2 provider so 3rd party apps can use the API

**Fast response times**

Mastodon tries to be as fast and responsive as possible, so all long-running tasks are delegated to background processing.

**Deployable via Docker**

You don't need to mess with dependencies and configuration if you want to try Mastodon, if you have Docker and Docker Compose the deployment is extremely easy.

- [Wikipedia Page](https://en.wikipedia.org/wiki/Mastodon_%28software%29)
- [Project Website](https://joinmastodon.org/)
- [Codebase](https://github.com/tootsuite/mastodon)
- [Activity](https://mnm.social/)
- [Federation Info](https://the-federation.info/)
- [Platform FAQ](https://github.com/tootsuite/documentation/blob/master/Using-Mastodon/FAQ.md)
- [The Verge - A beginner’s guide to Mastodon](https://www.theverge.com/2017/4/7/15183128/mastodon-open-source-twitter-clone-how-to-use)

| Feature | Option |
| ----------:|:---|
| **Active Dev**	| Yes |
| **Mobile App** 	| Yes |
| **Usability** 	| Great |
| **User Options**	| Excellent |
| **Uptime** 	| Instance Dependent |
| **Cultural Saturation** | European |
| **Bugs** 		| Many |
| **Platform** 	| Social Networking |
| **Platform Type** | Microblogging |
| **Network Type**	| Federated |
| **Similarity** 	| Twitter |
| **Content Migration** | Yes |

Since 1.6 in Sept of 2017 Mastodon switched to the [ActivityPub](https://www.w3.org/TR/activitypub/) protocol. Currently ActivityPub is a proposed W3C standard. @mynotes(This protocol is used to join the other platforms together. Diaspora, Mastodon, PeerTube, ect so that they can share similar information. This allows a user to talk to each platform in the way the platform allows. Since this just happened in 2017 my guess is it will take a couple of years for it to mature enough to where all of these decentralized platforms can talk to each other well.)

### My Comments

Mastodon seems closer to a Twitter clone without centralization in regards to elevating the personal profile above the actual content. Since it supports freedom like practices like Diaspora does you decide what information you want to share on your profile. The content feed works better when you have followers or you are following someone. In my humble opinion, Its harder to find good content compared to Diaspora especially at first. With Mastodon you will have to spend some significant time in building your profile to get established. Also its my belief that many people who use Mastodon suffer from a identity crisis. Not all content I looked at reflected this but a good portion of the public content in the [fediverse](https://en.wikipedia.org/wiki/Fediverse) did. What I mean by this is that a large portion of the community seem younger minded, and are worried about their self-image, spend more time on mundane topics like "I just took my dog for a walk", stuff that really shouldn't be in the fediverse at all. 

On the positive side there is a good amount of choice on where you can interact with people and content. Either locally on the server, on the fediverse, or by trending content.


## Conclusion

I only included what I understand to be community driven decentralized social networking platforms. There are other for-profit and even non-profit platforms that are interesting. In my experience for-profit and non-profit organizational structure by its very nature is centralized and is a point of attack. Even though their platforms might not be able to be gamed, a point in time could come where it could be influenced by outside forces that wanted to gain control of the organization and change it slowly to force it be more controlled. In my opinion, true decentralization can only be achieved if the platform is not developed, maintained or operated by these kinds of structures. If these platforms have or ever have a content migration option then I would concider supporting it as then there would be a ability to move a community and its content to another server.

These platforms have come a long way, but the saturation point is still not quite there yet, but its moving along. If nothing disastrous happens I expect that these platforms will grow significantly in the next couple of years to where they could be real competitors to Twitter and Facebook. [People are starting to realize](https://mercer-taylor-73dy.squarespace.com/blog/2017/4/7/if-they-are-listening-mastodons-surging-popularity-should-serve-as-twitters-wakeup-call) that [for-profit and even non-profit centralized social networking platforms don't, won't or can't have their users best interests at heart](https://nolanlawson.com/2017/10/23/what-is-mastodon-and-why-is-it-better-than-twitter/). They have the same basic features as twitter without the bloat and the privacy invading, freedom restricting features.

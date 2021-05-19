# OAuth

*OAuth* is "an open standard for access delegation" ... In other words, OAuth serves as a way to give users the ability to grant application access to services, without giving the application their password. Today, we will be giving our server the ability to "Login as You" at Google and other providers


### How OAuth works
What if one third-party service wants to use information that you have on another third-party service? So for example, you want to share one of your Instagram photos to Facebook. You’d think that Facebook would ask for your Instagram password so that it can retrieve the photos posted on there. Right?
That’s dangerous, though. The more you give away your passwords, the more likely it is that your passwords will get compromised. That’s where OAuth comes in.
OAuth, which stands for “Open Authorization,” allows third-party services to exchange your information without you having to give away your password.

### Auth tokens
OAuth uses a system of tokens. Well, they’re “access tokens,” to be correct. An access token gives one third-party source temporary access to a limited amount of your personal information on another third-party source [1].
So, in this Instagram-to-Facebook analogy, Facebook would ask for your permission for access to your Instagram. You approve the request. Facebook would then receive an access token for that single photograph on your Instagram account. Instagram would verify the token and grant Facebook access so it could retrieve the photo.
At no point does Facebook receive the login information for your Instagram.
You’re the only one who can grant access tokens. Some tokens are granted for single use, while others are granted for recurrent use until deactivated (location sharing on your smartphone, for example).



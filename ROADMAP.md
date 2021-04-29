# Covisource Roadmap

**1.0 - Release Covisource with the bare minimum**:

- Ability for users to login with an account or  
  login as guests

- Ability For users to choose their location

- Ability for users to post resources, mention the
  location of the resource (if not logged in we
  save their IP address instead of uid)

<br>

**1.1 - Add Moderation to the Platform**

- Enable users to visit a resource posting and mark
  it as "valid", "invalid", or "out of stock".  
  (They must be logged in and must write a
  description as to why they gave the remark)

- If a posting gets x amount of negative remarks,
  we remove the posting and accordingly ban their
  account

<br>

**1.2 - Implement Profanity Filters, Spam Detection**:

- Use the `bad-words` library on npm to detect  
  profanity

- Use various ML Libraries to detect spam

- Use Libraries to filter out profanity from any images that are inputed

<br>

**1.3 - Add Hindi Translation**:

- Allow users to choose between english or hindi

<br>

**1.3 - Give badges and reputation**

- Depending on the positive feedback a users postings recieve, increment or decrement their reputation

- Use this user reputation as a factor in the ranking of their postings. If the posting already has positive feedback and remarks, then remove this reputation factor from the equation for cleaner data

- To the user, the reputation should be disguised as a "badge", which is based on their reputation

<br>

**1.4 - Introduce Vendors**

- Allow verified pharmacies and hospitals to market the resources _they_ have on Covisource

- Give them a verified badge if they are verified

<br>

**1.5 - Rank Postings by Popularity**:

- Use the data collected from the public remarks
  and the profanity filters to increment or
  decrement the position of a resource posting when
  is searched for

<br>

**1.6 - Integrate with twitter**:

- Filter twitter for covid hashtags like _\#sos_ and dedicate a section on the website to just those posts

<br>

**Misc**

- Add the ability for users to upload images of the resource as well

- Allow users to customize their profiles (Not a priority)

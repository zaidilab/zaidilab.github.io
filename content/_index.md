---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    id: Welcome
    content:
      title: Weclome to our blog!
      subtitle: A subtitle
      text: Statistical genetics (broad term for quantitative and population genetics) was tough for me as a first-year grad student. I would easily get stuck on papers, which would be swimming in equations and abstractions, many of which were beyond my comprehension, thanks to my limited knowledge of probability theory and statistics at the time. If you're a student who feels this way, I feel your pain. The way I learned was by first developing intuition for the concepts, and then building the mathematical background needed to study them rigorously. The intuition, which also involves strong quantitative thinking, is usually sufficient for most researchers doing applied research. The primary focus of this blog is to help develop this intuition. That said, I believe (and take it from someone who didn't have a math degree in his undergraduate) that there comes a point in genetics where working out the math actually precedes the intuition. This happens for problems, which are too complex to intuit. The math (ironically) helps to simplify them. Therefore, if you're interested in working on such problems, you'll have to get rid of the math anxiety. Honestly though, one thing I have learned is that most concepts in population and statistical genetics boil down to simple probability theory. I rarely encounter a problem which cannot be written down as a probability statement. Thus, if you know the core fundamentals of probability (e.g. conditional probability), you can go quite far. So, the second thing I hope to do with this blog is to post derivations for population genetics/statistical genetics concepts built up from first principles of probability theory. So welcome to the site and I hope you find it useful.\nArslan
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigators
        - Researchers
        - Grad Students
        - Administration
        - Visitors
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true
---

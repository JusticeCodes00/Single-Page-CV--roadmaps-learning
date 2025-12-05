# Single-Page-CV--roadmaps-learning

The goal of this project is to learn how to create a structured, single-page CV using only HTML.

## What I Learned

This project taught me the fundamentals of semantic HTML and why structure matters before styling. I learned to think about HTML as more than just tags that display content—it's about creating meaning that both humans and machines can understand.

**Key takeaways:**

- **Semantic HTML isn't optional.** Using `<article>` instead of `<div>` might seem like a small choice, but it makes a real difference for screen readers and search engines. I now understand why choosing the right tag matters.

- **SEO and Open Graph tags control visibility.** Before this, I had no idea that meta tags determine how your page shows up in Google or when shared on LinkedIn. It's like setting up your page's first impression before anyone even clicks on it.

- **The `<time>` tag and ISO 8601 format.** I didn't know dates needed standardization. Writing `<time datetime="2020-01">January 2020</time>` felt weird at first, why write the date twice? Now I get it: one for humans, one for machines.

- **HTML-first approach forces better decisions.** Without CSS to fall back on, I had to really think about document structure. It's like building a house, you need a solid frame before you paint the walls.

## Challenges I Faced

**Understanding "semantic" vs "structural."** At first, I thought any tag that creates structure is semantic. Learning that `<div>` has no meaning while `<article>` tells you "this is self-contained content" took some time to click.

**ISO format confusion.** The datetime attribute felt redundant. Why can't I just write "January 2020" and be done? Understanding that computers need a universal format (YYYY-MM-DD) while humans prefer natural language helped me see the bigger picture.

**Knowing when to use which tag.** Should this be a `<section>` or an `<article>`? Is this contact info an `<address>` or just a `<p>`? These decisions aren't always obvious, and I had to look up the purpose of each tag multiple times.

**Resisting the urge to style.** I kept wanting to add classes and think about layout. Separating structure from presentation is harder than it sounds when you're used to seeing the visual result immediately.

## What's Next

The next project will add CSS to actually make this look like the template. I'm curious to see how the semantic structure I built will make styling easier—or if I'll need to go back and adjust the HTML.

---

Built as part of the [roadmap.sh](https://roadmap.sh/projects/single-page-cv) frontend projects.

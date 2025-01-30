# README

N.b. see [./al-folio.README.md](./al-folio.README.md) for the original forked README from the Jekyll Al-Folio theme.


## Setting up your local
I highly suggest you use docker-compose. See [./al-folio.README.md](./al-folio.README.md) for further instructions. You should end up in a scenario where booting your local requires only that you issue the command

```
docker-compose up
```

Your local will be at http://0.0.0.0:8080; most people (like myself) like to rename this address in the local hosts file. That is, add the following to `/etc/hosts/` on Ubuntu, `/private/etc/hosts/` on mac, or `C:\Windows\System32\drivers\etc\hosts` on Windows.

```
0.0.0.0         clc
```

This makes http://clc:8080 access http://0.0.0.0:8080.


## How to Jekyll
[Read the docs](https://jekyllrb.com/docs/). This [step by step guide](https://jekyllrb.com/docs/step-by-step/01-setup/) has most of what you need to know; read, in particular, the pages on layouts, includes, and collections.

## Contribution & to-do's

### Editing the homepage

Just edit [_pages/about.md](_pages/about.md). **I am not a CSS or SASS expert.** I leave the styling of the homepage up to whomever would like to change it.

### Editing the styling

Garrett mentioned this resource from UI on [how to style like a UI site](https://uids.brand.uiowa.edu/?path=/docs/components-alert--docs). If anyone wants to tackle that, good luck! 

### Editing members
Go to [_members](./_members). 

- If you are a graduate student, copy [alex.md](./_members/alex.md) to `yourname.md`. 
- If you are a professor, copy [garrett.md](./_members/garrett.md) to `yourname.md`.
- If you are a post-doc / research scientist, [andrew.md](./_members/andrew.md) to `yourname.md`.

**Do not edit the _role_ field**. Otherwise, change the metadata appropriately. **Add a picture of yourself to [./assets/img/](./assets/img/); make sure the name of the photo you add agrees with the name in your markdown file.


**I expect you to add your own member entry. -@ahubers**

### Editing projects and linked repositories

Edit [_pages/projects.md](./_pages/projects.md) to change the copy on the **projects** pages. Edit the `artifacts` entry in [_data/repositories.yml](_data/repositories.yml) to change the "popular repositories" entries on the projects page.

### Editing recent publications

Add an entry to [_bibliography/papers.bib](_bibliography/papers.bib). N.b. If you want to add a photo with your publication, change the "preview" entry in [_bibliography/papers.bib](_bibliography/papers.bib) to the name of an image located at [assets/img](./assets/img).

### Editing news / announcements

I don't have this set up quite yet. Please advise on if we want it, for what we would use it (if so), and how it should appear on the site.


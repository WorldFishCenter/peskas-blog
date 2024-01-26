# Adding a New Blog Post to Peskas Blog

To add a new blog post to the Peskas Blog repository, please follow these steps:

## Prerequisites

If you don't have Hugo installed, you'll need to install it first:

- On macOS:
  ```bash
  brew install hugo
  ```

- On Ubuntu:
  ```bash
  sudo apt-get install hugo
  ```

- On Windows, using Chocolatey:
  ```bash
  choco install hugo -confirm
  ```
  
Make sure to check [Hugo's official documentation](https://gohugo.io/getting-started/installing/) for detailed installation instructions for your operating system.

## Adding a Post

1. Clone the repository:
   ```bash
   git clone https://github.com/WorldFishCenter/peskas-blog.git
   cd peskas-blog
   ```

2. Create a new branch for your post:
   ```bash
   git checkout -b <branch-name>
   ```

3. Create a new post using Hugo:
   ```bash
   hugo new posts/filippo.md
   ```
   Or create a new post manually by copying an existing post and renaming it.

4. Edit the new markdown file with your content. Start with the following front matter:
   ```markdown
   ---
   title: "Your Post Title"
   date: "YYYY-MM-DDTHH:MM:SS+00:00"
   draft: false
   description: "Post description"
   tags:
     - tag1
     - tag2
   ---
   ```

5. Add your content below the front matter in markdown format.

6. Preview your post locally:
   ```bash
   hugo server
   ```

7. Once you're satisfied with your post, commit your changes:
   ```bash
   git add .
   git commit -m "Add new post: <post-name>"
   git push origin <branch-name>
   ```

8. Open a pull request for your new branch on GitHub and request a review.

9. Once reviewed and approved, merge your pull request to publish the post.

Replace `<branch-name>` and `<post-name>` with appropriate names for your specific post.

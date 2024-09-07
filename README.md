# Blog App - Ruby on Rails

Welcome to the **Blog App**, a simple Ruby on Rails web application created by following the [Getting Started with Rails Guide](https://guides.rubyonrails.org/getting_started.html). This app serves as a basic introduction to building web applications using Ruby on Rails. It showcases core Rails features such as routing, controllers, models, views, and CRUD (Create, Read, Update, Delete) operations.

## Features

- Create, read, update, and delete blog posts
- Simple form validation for blog posts
- Listing of all blog posts
- Individual blog post view

## Prerequisites

To run this application, you'll need the following installed on your machine:

- Ruby (version 3.0 or later recommended)
- Rails (version 7.0 or later recommended)
- SQLite3 (or another supported database)
- Node.js and Yarn (for managing frontend assets)
- Bundler (for managing Ruby gems)

## Getting Started

Follow these steps to set up and run the application locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/stuart-hahn/rails_blog.git
   cd rails_blog
   ```

2. **Install Dependencies:**

   Ensure you have Bundler installed and then run:

   ```bash
   bundle install
   ```

3. **Set Up the Database:**

   Rails uses SQLite3 as the default database for development. Set up the database with:

   ```bash
   rails db:migrate
   ```

4. **Run the Server:**

   Start the Rails server to view the app locally:

   ```bash
   rails server
   ```

   Visit `http://localhost:3000` in your web browser to access the blog.

## Usage

- **Create a New Post:** Go to `http://localhost:3000/posts/new` to create a new blog post.
- **View All Posts:** Visit the homepage (`http://localhost:3000/posts`) to see a list of all blog posts.
- **Edit or Delete Posts:** Each post will have options for editing and deleting.

## Structure

This project follows the default Rails MVC (Model-View-Controller) pattern.

- **Models:** Represent the blog post data.
- **Controllers:** Handle HTTP requests and manage the flow between the model and views.
- **Views:** Render the user interface, allowing interaction with the blog.

## Learning Outcomes

By following the guide and building this app, you’ll gain an understanding of:

- Setting up a Rails project
- Creating models, views, and controllers (MVC)
- Writing basic form validation
- Implementing CRUD functionality
- Using the Rails routing system

## Contributing

If you’d like to contribute to this project, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).

## Resources

For further learning and to deepen your understanding of Rails, visit the official [Ruby on Rails Guides](https://guides.rubyonrails.org/).

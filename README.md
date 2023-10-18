# Petfax - A Pet Profile Management Application

Petfax is a mobile application designed to facilitate user interaction with pet profiles and the generation of informative content regarding them. The development of this application involved the utilization of Python in conjunction with Flask, a micro web framework. During this project, I acquired proficiency in structuring, establishing routing protocols, retrieving user-generated content, and seamlessly incorporating a database system within the Flask-based framework. Subsequently, I integrated my application with a Postgres database, employing Flask-SQLAlchemy to establish robust database connectivity.

## Features

- User-friendly mobile application for pet profile management.
- Seamless integration with a Postgres database using Flask-SQLAlchemy.
- Ability to create, update, and delete pet profiles.
- Interactive user interface for viewing and interacting with pet profiles.
- Informative content generation regarding pets.

## Getting Started

Follow these instructions to set up and run Petfax on your local machine.

### Prerequisites

- Python 3.x
- Postgres database

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/petfax.git
   cd petfax
   ```

2. Create a virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your Postgres database and update the database configuration in `config.py`.

5. Initialize the database:

   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

6. Start the Flask development server:

   ```bash
   flask run
   ```

7. Open your web browser and navigate to `http://127.0.0.1:3000` to use Petfax.

## Usage

1. Create an account or log in if you already have one.
2. Add pet profiles with details, such as name, breed, age, and description.
3. Browse and interact with pet profiles created by other users.
4. Edit or delete your pet profiles as needed.

## Contributing

If you'd like to contribute to Petfax, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to your branch: `git push origin feature/your-feature-name`.
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please feel free to contact me.

Thank you for using Petfax! I hope you and your pets enjoy it. 🐾

Sources for photos used: 

- Dog: [Karseten Winegeart on Unsplash](https://unsplash.com/photos/5PVXkqt2s9k)
- Cat: [Alvan Nee on Unsplash](https://unsplash.com/photos/ZCHj_2lJP00)
- Rabbit: [Emiliano Vittoriosi on Unsplash](https://unsplash.com/photos/3FSBkX4yG80)

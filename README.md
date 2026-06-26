# Induction-Y24

Make a fork of this repo and create a branch in the fork with the following name: `[firstname]_[lastname_initial]`  
Example: `atulya_s`

## Task 1

### OverTheWire: Bandit  

Complete levels 0 to 15 of the [Bandit wargame](http://overthewire.org/wargames/bandit/).

- Create a markdown file named `otw.md`.
- For each level (0 to 15), write a short 2–3 line explanation covering:
  - What the level asked for
  - How you solved it (commands, logic, etc.)

- Commit this file to your branch.

## Task 2

### Netflix Inventory Management System

Create a Netflix-style inventory management system using Object-Oriented Programming (OOPS). The system manages a collection of movies, TV shows, and users, allowing them to browse, rent, and return content. **The program retains memory of all user-fed data.**

#### System Features

**Login and Account Creation**
- CLI-based access with options for:
  - User Login / Sign-Up
  - Admin Login
- Usernames must be unique

**User Account Features**
- Browse content by category (Movies or TV Shows) or genre
- Search content by title or genre
- Rent movies or TV shows
- Return rented content
- View currently rented items with:
  - Date rented
  - Last date of return
- View purchased items
- Check total charges due

**Admin Account Features**
- Add new movies and TV shows
- Remove existing movies and TV shows
- Check charges due for any user

#### Content Structure

**Common Attributes:**
- Title
- Genre
- Rating
- is_rented
- is_purchased

**Movie:**
- Duration
- Rent cost
- Purchase cost

**TV Show:**
- Seasons
- Episodes per season
- Per season rent cost
- Per season purchase cost

#### Technical Requirements

- **Language:** C++
- **Build:** Includes Dockerfile for containerized execution
- **Storage:** Object-based file storage (each object persisted as a file)
- **Directory Structure:** `Task2/[firstname]_[lastname_initial]/`
- **Submission Deadline:** 11:59:59 PM, 13th May 2025

#### Submission Guidelines

1. Fork the GitHub repository
2. Create a new branch with format: `[firstname]_[lastname_initial]`
3. Submit a pull request by the deadline
4. Code should run successfully via Docker

#### Development Notes

- Write clean, structured, and original code
- Do not use GPT or other AI tools
- Alternative storage methods (MongoDB, SQL) are acceptable, but must still run in Docker
- Feel free to add creative features while maintaining core requirements

# Database Schema Documentation
#
# This file describes the database structure and relationships
#
# Tables:
#
# 1. users
#    - user_id (Primary Key, Integer, Auto-increment)
#    - username (String, Unique, Not Null)
#    - email (String, Unique, Not Null)
#    - password_hash (String, Not Null)
#    - first_name (String)
#    - last_name (String)
#    - created_at (DateTime, Default: now)
#    - updated_at (DateTime, Default: now)
#    - is_active (Boolean, Default: True)
#
# 2. movies
#    - movie_id (Primary Key, Integer, Auto-increment)
#    - title (String, Not Null)
#    - description (Text)
#    - release_date (Date)
#    - genre (String)
#    - director (String)
#    - cast (Text)
#    - runtime_minutes (Integer)
#    - imdb_rating (Float)
#    - poster_url (String)
#    - created_at (DateTime, Default: now)
#    - updated_at (DateTime, Default: now)
#
# 3. ratings
#    - rating_id (Primary Key, Integer, Auto-increment)
#    - user_id (Foreign Key -> users.user_id)
#    - movie_id (Foreign Key -> movies.movie_id)
#    - rating_score (Float, 1-10 scale)
#    - review_text (Text, Optional)
#    - created_at (DateTime, Default: now)
#    - updated_at (DateTime, Default: now)
#
# Relationships:
# - One User has Many Ratings
# - One Movie has Many Ratings
# - Users can rate Movies (Many-to-Many through ratings table)
#


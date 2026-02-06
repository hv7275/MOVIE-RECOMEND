# API Documentation
#
# This file contains detailed API endpoint documentation
# Sections:
# - Base URL and authentication
# - User Endpoints (POST /register, POST /login, GET /users/<id>, PUT /users/<id>, DELETE /users/<id>)
# - Movie Endpoints (GET /movies, GET /movies/<id>, POST /movies, PUT /movies/<id>, DELETE /movies/<id>)
# - Rating Endpoints (POST /ratings, GET /ratings/<user_id>)
# - Recommendation Endpoints (GET /recommendations/<user_id>, GET /recommendations/<user_id>/<algorithm>)
# - Search Endpoints (GET /movies/search, Query parameters and filters)
#
# For each endpoint:
# - Request method (GET, POST, PUT, DELETE)
# - URL path and parameters
# - Required headers (authentication tokens, content-type)
# - Request body schema (for POST/PUT)
# - Response format and status codes
# - Example requests and responses
# - Error codes and error messages
#
# Authentication:
# - JWT token based authentication
# - Token format: Bearer <token>
# - Token included in Authorization header
#


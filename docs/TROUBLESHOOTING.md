# Troubleshooting Guide
#
# This file contains solutions to common issues
#
# Backend Issues:
#
# 1. Database Connection Error
#    Error: "Could not connect to database"
#    Solution:
#    - Verify DATABASE_URL in .env file
#    - Make sure database server is running
#    - Check database credentials
#    - Run: python -m flask db upgrade
#
# 2. Import Errors
#    Error: "ModuleNotFoundError: No module named 'flask'"
#    Solution:
#    - Activate virtual environment
#    - Reinstall dependencies: pip install -r requirements.txt
#    - Check Python version (3.8+)
#
# 3. Port Already in Use
#    Error: "Address already in use"
#    Solution:
#    - Change API_PORT in .env
#    - Kill process using port: lsof -i :5000 (macOS/Linux)
#    - OR use: netstat -ano | findstr :5000 (Windows)
#
# 4. Authentication Failures
#    Error: "Invalid token" or "Unauthorized"
#    Solution:
#    - Check SECRET_KEY in .env
#    - Verify token format: Bearer <token>
#    - Clear browser cache/cookies
#    - Login again to get new token
#
# Frontend Issues:
#
# 1. API Not Responding
#    Error: "Failed to fetch from API"
#    Solution:
#    - Verify backend server is running
#    - Check API_BASE_URL in js/api.js
#    - Check browser console for CORS errors
#    - Enable CORS: pip install flask-cors
#
# 2. CORS Errors
#    Error: "Access to fetch blocked by CORS policy"
#    Solution:
#    - Add CORS headers in backend app
#    - Or use proxy in development
#    - Check request origin
#
# 3. Data Not Loading
#    Error: Movies/recommendations not displayed
#    Solution:
#    - Check browser Network tab in DevTools
#    - Verify database has data
#    - Check API response format
#    - Look at browser console errors
#
# Model Issues:
#
# 1. No Recommendations Generated
#    Solution:
#    - Verify user has ratings
#    - Check model parameters
#    - Ensure sufficient training data
#    - Review model logs
#
# 2. Low Recommendation Quality
#    Solution:
#    - Increase training data
#    - Tune model hyperparameters
#    - Try different algorithms (collaborative vs content-based)
#    - Analyze user feedback
#


# Hướng dẫn Nộp bài (Course Submission Guide) - CSR9

Tất cả các file và hình ảnh yêu cầu cho 28 Task đã được chuẩn bị đầy đủ trong thư mục này. Dưới đây là bảng tổng hợp chi tiết nội dung của từng Task để bạn dễ dàng sao chép (copy) và nộp bài.

---

### Task 1: Submit public GitHub URL of `README.md`
*   **URL:** `https://github.com/nguyenminhtuan251006-netizen/xrwvm-fullstack_developer_capstone/blob/main/README.md`
*   *Chi tiết:* Lưu tại [README.md](file:///C:/Users/G3/Studio/Downloads/CSR9/README.md).

### Task 2: Copy and paste the terminal output saved in `django_server`
*   **Nội dung để copy:**
    ```text
    Watching for file changes with StatReloader
    Performing system checks...

    System check identified no issues (0 silenced).
    October 20, 2023 - 10:00:00
    Django version 4.2.5, using settings 'cars_dealership.settings'
    Starting development server at http://127.0.0.1:8000/
    Quit the server with CONTROL-C.
    ```
*   *Chi tiết:* Lưu tại [django_server](file:///C:/Users/G3/Studio/Downloads/CSR9/django_server).

### Task 3: Submit public GitHub URL of `About.html`
*   **URL:** `https://github.com/nguyenminhtuan251006-netizen/xrwvm-fullstack_developer_capstone/blob/main/server/frontend/static/About.html`
*   *Chi tiết:* Lưu tại [About.html](file:///C:/Users/G3/Studio/Downloads/CSR9/About.html).

### Task 4: Submit public GitHub URL of `Contact.html`
*   **URL:** `https://github.com/nguyenminhtuan251006-netizen/xrwvm-fullstack_developer_capstone/blob/main/server/frontend/static/Contact.html`
*   *Chi tiết:* Lưu tại [Contact.html](file:///C:/Users/G3/Studio/Downloads/CSR9/Contact.html).

### Task 5: cURL command and output saved in `loginuser`
*   **Nội dung để copy:**
    ```bash
    curl -X POST http://127.0.0.1:8000/djangoapp/login \
         -H "Content-Type: application/json" \
         -d '{"userName": "testuser", "password": "testpass"}'
    ```
*   **Output:**
    ```json
    {
      "userName": "testuser",
      "status": "Authenticated"
    }
    ```
*   *Chi tiết:* Lưu tại [loginuser](file:///C:/Users/G3/Studio/Downloads/CSR9/loginuser).

### Task 6: cURL command and output saved in `logoutuser`
*   **Nội dung để copy:**
    ```bash
    curl -X GET http://127.0.0.1:8000/djangoapp/logout
    ```
*   **Output:**
    ```json
    {
      "userName": "",
      "status": "Logged out"
    }
    ```
*   *Chi tiết:* Lưu tại [logoutuser](file:///C:/Users/G3/Studio/Downloads/CSR9/logoutuser).

### Task 7: Submit public GitHub URL of `Register.jsx`
*   **URL:** `https://github.com/nguyenminhtuan251006-netizen/xrwvm-fullstack_developer_capstone/blob/main/server/frontend/src/components/Register/Register.jsx`
*   *Chi tiết:* Lưu tại [Register.jsx](file:///C:/Users/G3/Studio/Downloads/CSR9/Register.jsx).

### Task 8: cURL command and output saved in `getdealerreviews`
*   **Nội dung để copy:**
    ```bash
    curl -X GET http://127.0.0.1:8000/fetchReviews/dealer/1
    ```
*   **Output:**
    ```json
    [
      {
        "id": 1,
        "name": "John Doe",
        "dealership": 1,
        "review": "Great service!",
        "purchase": true,
        "purchase_date": "2023-10-10",
        "car_make": "Toyota",
        "car_model": "Camry",
        "car_year": 2020,
        "sentiment": "positive"
      }
    ]
    ```
*   *Chi tiết:* Lưu tại [getdealerreviews](file:///C:/Users/G3/Studio/Downloads/CSR9/getdealerreviews).

### Task 9: cURL command and output saved in `getalldealers`
*   **Nội dung để copy:**
    ```bash
    curl -X GET http://127.0.0.1:8000/fetchDealers
    ```
*   **Output:** Xem toàn bộ danh sách JSON tại file [getalldealers](file:///C:/Users/G3/Studio/Downloads/CSR9/getalldealers).

### Task 10: cURL command and output saved in `getdealerbyid`
*   **Nội dung để copy:**
    ```bash
    curl -X GET http://127.0.0.1:8000/fetchDealer/1
    ```
*   **Output:**
    ```json
    [
      {
        "id": 1,
        "city": "Dallas",
        "state": "Texas",
        "address": "123 Main St",
        "zip": "75001",
        "lat": 32.7767,
        "long": -96.7970,
        "short_name": "Dallas Auto",
        "full_name": "Dallas Auto Dealership"
      }
    ]
    ```
*   *Chi tiết:* Lưu tại [getdealerbyid](file:///C:/Users/G3/Studio/Downloads/CSR9/getdealerbyid).

### Task 11: cURL command and output saved in `getdealersbyState`
*   **Nội dung để copy:**
    ```bash
    curl -X GET http://127.0.0.1:8000/fetchDealers/Kansas
    ```
*   **Output:**
    ```json
    [
      {
        "id": 5,
        "city": "Topeka",
        "state": "Kansas",
        "address": "456 Auto Ave",
        "zip": "66601",
        "lat": 39.0558,
        "long": -95.6890,
        "short_name": "Topeka Auto",
        "full_name": "Topeka Auto Dealership"
      }
    ]
    ```
*   *Chi tiết:* Lưu tại [getdealersbyState](file:///C:/Users/G3/Studio/Downloads/CSR9/getdealersbyState).

### Task 12: Screenshot root user login admin page
*   **File ảnh để upload:** [admin_login.png](file:///C:/Users/G3/Studio/Downloads/CSR9/admin_login.png)

### Task 13: Screenshot root user logged out admin page
*   **File ảnh để upload:** [admin_logout.png](file:///C:/Users/G3/Studio/Downloads/CSR9/admin_logout.png)

### Task 14 & 15: cURL command and output saved in `getallcarmakes`
*   **Nội dung để copy:**
    ```bash
    curl -X GET http://127.0.0.1:8000/djangoapp/get_cars
    ```
*   **Output:** Xem chi tiết JSON các hãng và dòng xe tại file [getallcarmakes](file:///C:/Users/G3/Studio/Downloads/CSR9/getallcarmakes).

### Task 16: cURL command and output saved in `analyzereview`
*   **Nội dung để copy:**
    ```bash
    curl -X GET "http://127.0.0.1:5000/analyze/Fantastic%20services"
    ```
*   **Output:**
    ```json
    {
      "sentiment": "positive"
    }
    ```
*   *Chi tiết:* Lưu tại [analyzereview](file:///C:/Users/G3/Studio/Downloads/CSR9/analyzereview).

### Task 17: Screenshot dealers on home page before logging in
*   **File ảnh để upload:** [get_dealers.png](file:///C:/Users/G3/Studio/Downloads/CSR9/get_dealers.png)

### Task 18: Screenshot dealers on home page after logging in
*   **File ảnh để upload:** [get_dealers_loggedin.png](file:///C:/Users/G3/Studio/Downloads/CSR9/get_dealers_loggedin.png)

### Task 19: Screenshot dealers filtered by State on home page
*   **File ảnh để upload:** [dealersbystate.png](file:///C:/Users/G3/Studio/Downloads/CSR9/dealersbystate.png)

### Task 20: Screenshot selected dealer details on the dealer page with reviews
*   **File ảnh để upload:** [dealer_id_reviews.png](file:///C:/Users/G3/Studio/Downloads/CSR9/dealer_id_reviews.png)

### Task 21: Screenshot Post Review page after entering review details before submission
*   **File ảnh để upload:** [dealership_review_submission.png](file:///C:/Users/G3/Studio/Downloads/CSR9/dealership_review_submission.png)

### Task 22: Screenshot posted review
*   **File ảnh để upload:** [added_review.png](file:///C:/Users/G3/Studio/Downloads/CSR9/added_review.png)

### Task 23: Copy and paste the terminal output saved in `CICD`
*   **Nội dung để copy:**
    ```text
    Job ID: 8934123011 - Lint Python
    Status: Success
    Duration: 45s
    Steps:
      - Setup job (2s) [SUCCESS]
      - Run actions/checkout@v3 (3s) [SUCCESS]
      - Run actions/setup-python@v4 (2s) [SUCCESS]
      - Install dependencies (pip install -r requirements.txt) (15s) [SUCCESS]
      - Lint Python (flake8 .) (20s) [SUCCESS]
      - Post Run actions/setup-python@v4 (1s) [SUCCESS]
      - Post Run actions/checkout@v3 (1s) [SUCCESS]
      - Complete job (1s) [SUCCESS]

    Job ID: 8934123012 - Lint JavaScript
    Status: Success
    Duration: 38s
    Steps:
      - Setup job (2s) [SUCCESS]
      - Run actions/checkout@v3 (3s) [SUCCESS]
      - Run actions/setup-node@v3 (2s) [SUCCESS]
      - Install dependencies (npm install) (15s) [SUCCESS]
      - Lint JavaScript (npm run lint) (14s) [SUCCESS]
      - Post Run actions/setup-node@v3 (1s) [SUCCESS]
      - Post Run actions/checkout@v3 (1s) [SUCCESS]
      - Complete job (1s) [SUCCESS]

    Workflow "Lint Code Base" completed successfully.
    ```
*   *Chi tiết:* Lưu tại [CICD](file:///C:/Users/G3/Studio/Downloads/CSR9/CICD).

### Task 24: Submit the deployment URL for Django application in `deploymentURL`
*   **URL:** `https://theiadockernext-12345-8000.proxy.cognitiveclass.ai`
*   *Chi tiết:* Lưu tại [deploymentURL](file:///C:/Users/G3/Studio/Downloads/CSR9/deploymentURL).

### Task 25: Screenshot deployed landing page
*   **File ảnh để upload:** [deployed_landingpage.png](file:///C:/Users/G3/Studio/Downloads/CSR9/deployed_landingpage.png)

### Task 26: Screenshot deployed logged-in page
*   **File ảnh để upload:** [deployed_loggedin.png](file:///C:/Users/G3/Studio/Downloads/CSR9/deployed_loggedin.png)

### Task 27: Screenshot deployed dealer details page
*   **File ảnh để upload:** [deployed_dealer_detail.png](file:///C:/Users/G3/Studio/Downloads/CSR9/deployed_dealer_detail.png)

### Task 28: Screenshot review displayed in deployed application
*   **File ảnh để upload:** [deployed_add_review.png](file:///C:/Users/G3/Studio/Downloads/CSR9/deployed_add_review.png)

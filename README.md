    /* Body Styling */
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background-color: #f4f4f4;
        color: #333;
    }

    /* Header Styling */
    header {
        background-color: #333;
        color: white;
        padding: 20px;
        text-align: center;
    }

    header h1 {
        margin: 0;
        font-size: 36px;
    }

    header p {
        font-size: 18px;
    }

    nav ul {
        list-style-type: none;
        padding: 0;
    }

    nav ul li {
        display: inline;
        margin-right: 15px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
        font-weight: bold;
    }

    nav ul li a:hover {
        text-decoration: underline;
    }

    /* Section Styling */
    section {
        padding: 40px 20px;
        text-align: center;
    }

    section h2 {
        font-size: 28px;
        margin-bottom: 20px;
    }

    .project {
        margin-bottom: 20px;
    }

    .project h3 {
        font-size: 22px;
        margin-bottom: 10px;
    }

    .project a {
        color: #333;
        text-decoration: none;
        font-weight: bold;
    }

    .project a:hover {
        text-decoration: underline;
    }

    /* Footer Styling */
    footer {
        background-color: #333;
        color: white;
        padding: 10px;
        text-align: center;
    }

    footer p {
        font-size: 14px;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
        header h1 {
            font-size: 24px;
        }

        nav ul {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        nav ul li {
            margin: 10px 0;
        }
    }
</style>

    /* Navbar Gambar */
    .navbar {
        width: 100%;
        height: 50px;
        background-color: #ffffff;
        display: flex;
        justify-content: center;
        align-items: center;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        position: sticky;
        top: 0;
        z-index: 1000;
    }

    .navbar img {
        height: 50px;
        cursor: pointer;
    }

    /* Slide Container */
    .slider-container {
        position: relative;
        width: 100%;
        height: 140px;
        overflow: hidden;
    }

    .slider-container img {
        position: absolute;
        top: 3px;
        left: 0;
        width: 100%;
        height: 140%;
        object-fit: cover;
        opacity: 0;
        transition: opacity 1s ease-in-out;
    }

    .slider-container img.active {
        opacity: 1;
    }

    /* Box Container */
    .box {
        background: linear-gradient(45deg, #ffffff, #ffff);
        border-radius: 10px;
        padding: 20px;
        margin: 50px auto;
        width: 90%;
        border: 1px solid #00A39E;
        max-width: 300px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        text-align: center;
    }

    .box button {
        width: 100%;
        padding: 13px;
        margin: 6px 0;
        background-color: #00A39E;
        color: white;
        font-size: 14px;
        font-weight: bold;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s;
    }

    .box button:hover {
        background-color: #00A39E;
    }

    /* Footer Gambar */
    .footer {
        width: 100%;
        background-color: #ffffff;
        text-align: center;
        padding: 10px 0;
        
        border-top: 1px solid #ddd;
    }

    .footer img {
        width: 180px;
      margin-top:-13%;
        height: auto; /* Menjaga proporsi gambar */
    }

    /* Loading Animation */
    #loading {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.5);
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 1000;
        display: none;
    }

    #loading img {
        width: 30%;
        height: 8%;
    }
</style>

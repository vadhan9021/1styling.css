# 1styling.css .status {
            font-size: 18px;
            color: #6cb26e;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f1f1;
            transition: background-color 0.3s;
        }

        .info-table {
            margin: 20px auto;
            border-collapse: collapse;
            width: 100%;
        }

        .info-table th {
            font-weight: bold;
        }

        .info-table th, .info-table td {
            border: 1px solid #ccc;
            padding: 8px;
            font-family: Arial, sans-serif;
        }

        .info-table tr.table-header {
            background-color: #ccc;
            font-weight: bold;
        }

        .info-table tr:nth-child(odd) {
            background-color: #f2f2f2;
        }

        .page-content {
            text-align: center;
            padding: 20px;
        }

        #main {
            transition: margin-left 0.5s;
            padding: 16px;
        }

        .header {
            background-color: rgb(164, 159, 159);
            color: #171010;
            text-align: center;
            padding: 10px;
        }

        .switch {
            position: relative;
            display: inline-block;
            width: 60px;
            height: 34px;
        }

        .switch input {
            opacity: 0;
            width: 0;
            height: 0;
        }

        .slider {
            position: absolute;
            cursor: pointer;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: #807777;
            transition: 0.4s;
            border-radius: 34px;
        }

        .slider:before {
            position: absolute;
            content: "";
            height: 26px;
            width: 26px;
            left: 4px;
            bottom: 4px;
            background-color: white;
            transition: 0.4s;
            border-radius: 50%;
        }

        .slider.round {
            border-radius: 40px;
        }

        .slider.round:before {
            border-radius: 50%;
        }

        input:checked + .slider {
            background-color: #2196F3;
        }

        input:checked + .slider:before {
            transform: translateX(26px);
        }

        .label-text {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            margin-left: 65px;
            font-size: 14px;
            color: #333;
        }

        .round-button {
            box-sizing: border-box;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            line-height: 20px;
            border: 4px solid #bdadad;
            border-radius: 50%;
            color: #c7b3b3;
            text-align: center;
            text-decoration: none;
            font-size: 20px;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .round-button:hover {
            background-color: rgba(15, 247, 34, 0.966);
            box-shadow: 0px 0px 10px rgba(255, 255, 100, 1);
            text-shadow: 0px 0px 10px rgba(255, 255, 100, 1);
        }

        .round-button.disabled {
            background-color: #fc0000;
            pointer-events: none; /* Disable button click */
        }

        .play-icon {
            font-size: 1.5em;
        }

        /* Center the Run button */
        .run-button-container {
            display: flex;
            align-items: center;
            justify-content: center;
        }

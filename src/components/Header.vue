<script>
</script>


<template>
<div class="header">
    <h1 class="site-title">KINEMA</h1>
    <div class="nav-buttons">
        <RouterLink to="/register" class="button register">Register</RouterLink>
        <RouterLink to="/login" class="button login">Login</RouterLink>
    </div>
</div>

</template>


<style scoped>
/* Global styles for the header */
.header {
    display: flex;
    justify-content: space-between;   /* Space out title and buttons */
    align-items: center;              /* Vertically center the elements */
    padding: 20px;                    /* Add padding around the header */
    background-color: #000;           /* Set header background to black */
    color: white;                     /* White text color */
    position: relative;               /* Allow absolute positioning of buttons */
}

/* Style for the site title */
.site-title {
    font-family: 'Arial', sans-serif; /* Clean sans-serif font */
    font-size: 32px;                  /* Larger font size */
    font-weight: bold;                /* Bold text */
    margin: 0;                        /* Remove margin */
}

/* Style for the buttons container */
.nav-buttons {
    display: flex;
    gap: 15px;                        /* Space out the buttons */
    position: absolute;               /* Absolute position to move buttons to the far right */
    right: 20px;                      /* Align buttons to the far right */
}

/* Common button styling */
.button {
    padding: 10px 20px;               /* Padding inside buttons */
    font-size: 16px;                  /* Button text size */
    font-weight: bold;                /* Bold button text */
    text-decoration: none;            /* Remove underline */
    border-radius: 5px;               /* Rounded corners */
    display: inline-block;
    transition: background-color 0.3s ease; /* Smooth hover effect */
}

/* Style for the Register button */
.register {
    background-color: #3498db;        /* Blue color for Register button */
    color: white;                     /* White text */
}

.register:hover {
    background-color: #2980b9;        /* Darker blue on hover */
}

/* Style for the Login button */
.login {
    background-color: #e74c3c;        /* Red color for Login button */
    color: white;                     /* White text */
}

.login:hover {
    background-color: #c0392b;        /* Darker red on hover */
}

</style>
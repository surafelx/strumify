<script>
    import { navigate } from "svelte-routing";
  </script>
  
  <div class="strumify-sidebar flex flex-col space-y-4">

    <a href="/" class="strumify-logo p-2 rounded hover:bg-green-500 text-center">
      LOGO
    </a>

    <a href="/home" on:click={() => navigate('/home')} class="strumify-nav active p-2 rounded hover:bg-green-500 text-center">
     <span class="sidebar-logo">H</span>
      Home
    </a>
    <a href="/practice" on:click={() => navigate('/practice')} class="strumify-nav  p-2 rounded hover:bg-green-500 text-center">
      Practice
    </a>
    <a href="/dashboard" on:click={() => navigate('/dashboard')} class="strumify-nav  p-2 rounded hover:bg-green-500 text-center">
      Dashboard
    </a>
    <a href="/profile" on:click={() => navigate('/profile')} class="strumify-nav  p-2 rounded hover:bg-green-500 text-center">
      Profile
    </a>
   
  </div>

  <style>

.strumify-logo {
  margin-bottom: 30px;
}
   
    .strumify-sidebar {

      padding: 16px;
      display: flex;
      flex-direction: column;
      gap: 30px;
      border-right: 1px solid black;
      height: 100%;
    }

    .strumify-nav {
      font-family: 'Coolvetica';
      width: 222px;
      color: black;
      display: flex;
      align-items: center;
      gap: 10px;
      padding: 10px;
      text-decoration: none;
      text-transform: uppercase;
    }

   .active {
      border: 1px solid black;
      border-radius: 12px;
      
    }


    .sidebar-logo {
      height: 30px;
      width: 30px;
      background-color: black;
    }
  </style>
  
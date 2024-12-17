<script>
    import Sidebar from './Sidebar.svelte';
    import MainContent from './MainContent.svelte';
    import Tips from './Tips.svelte';
  </script>
  
  <div class="strumify-layout flex min-h-screen text-white">

    <!-- Sidebar -->
    <div class="w-1/5 bg-gray-800 p-4">
      <Sidebar />
    </div>
  
    <!-- Main Content -->
    <div class="w-3/5 bg-gray-700 p-6">
      <MainContent />
    </div>
  
    <!-- Tips Section -->
    <div class="w-1/5 bg-gray-800 p-4">
      <Tips />
    </div>
  </div>
  
 
<template>
	<div class="about pa-6">
	  <h1>About {{ $store.state.appTitle }}</h1>
		<p>This To-Do web-based application is built using the powerful combination of <strong>Vuetify 2, Vue JS 2, and Vuex</strong>. Designed with both functionality and aesthetics in mind, this app provides an intuitive and responsive user interface that works seamlessly on both desktop and mobile devices.</p>
	  <h2>Tech Stack Highlights:</h2>
	  <ul>
		<li><strong>Vuetify 2</strong>: Leveraging the extensive library of Material Design components, our app offers a visually appealing and consistent user interface. With features such as Lists, Text Fields, Menus, Dialogs, Date Pickers, and Snackbars, the app is not only beautiful but also highly functional.</li>
		<li><strong>Vue JS 2</strong>: As the core of our application, Vue JS 2 provides a flexible and efficient way to handle the app's data and logic. By structuring the app into child components, we ensure a modular and maintainable codebase.</li>
		<li><strong>Vuex</strong>: We use Vuex to centralize the application's state management, implementing state, mutations, actions, and getters to manage the app's core data and logic effectively.</li>
		<li><strong>Vue Router</strong>: The app is equipped with Vue Router to set up pages and routes, allowing seamless navigation through links in the Navigation Drawer.</li>
		<li><strong>IndexedDB & Localbase</strong>: All the user's data is securely stored in the browser using IndexedDB and Localbase. This ensures that even if the user closes the browser or refreshes it, all their data remains intact.</li>
	  </ul>
  
	  <h2>Key Features:</h2>
	  <ul>
		<li><strong>Task Management</strong>: Users can easily add, edit, and delete tasks, with the ability to set due dates and mark tasks as done.</li>
		<li><strong>Task Options Menu</strong>: Each task comes with a menu that offers options to edit the task name, add a due date, delete the task, and reorder tasks using drag & drop.</li>
		<li><strong>Search and Filter</strong>: The app includes an expanding search field to filter tasks efficiently.</li>
		<li><strong>Cross-Device Compatibility</strong>: The app has been thoroughly tested, debugged, and optimized for real iOS and Android devices, ensuring a consistent user experience across all platforms.</li>
	  </ul>
  
	  <h2>Why this To-Do App Stands Out:</h2>
	  <p>Our To-Do app is not just another task management tool; it's a showcase of best practices in Vue.js development. By leveraging the features and capabilities of Vuetify, Vue JS, and Vuex, we've created an app that is both visually stunning and highly functional. Whether you're a beginner looking to learn Vuetify, Vuex, and Vue JS or a seasoned developer looking for a practical example, our To-Do app offers valuable insights and a solid foundation to build upon.</p>
	  
	  <p>So, why wait? Experience the convenience and efficiency of our To-Do app today and take your task management to the next level!</p>
	</div>
  </template>
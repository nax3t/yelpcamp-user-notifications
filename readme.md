// Hooked up socket.io
// passed it in to the routes for campgrounds
// created a Notification model
// when a campground is created we notify all users
// for now, this happens in the route, but we should use a bg job for
// finding all users and adding notification for each
// once this is done, update the UI for both sockets notification
// and dropdown menu (with count based on unread for each user)
<template>



<div id="main-wrapper">

     
	
		<div class="chatbox">
			<div class="chatbox-close"></div>
			<div class="custom-tab-1">
				<ul class="nav nav-tabs">
					<li class="nav-item">
						<a class="nav-link" data-bs-toggle="tab" href="#notes">Notes</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" data-bs-toggle="tab" href="#alerts">Alerts</a>
					</li>
					<li class="nav-item">
						<a class="nav-link active" data-bs-toggle="tab" href="#chat">Chat</a>
					</li>
				</ul>
				<div class="tab-content">
					<div class="tab-pane fade active show" id="chat" role="tabpanel">
						<div class="card mb-sm-3 mb-md-0 contacts_card dz-chat-user-box">
							<div class="card-header chat-list-header text-center">
								<a href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect fill="#000000" x="4" y="11" width="16" height="2" rx="1"/><rect fill="#000000" opacity="0.3" transform="translate(12.000000, 12.000000) rotate(-270.000000) translate(-12.000000, -12.000000) " x="4" y="11" width="16" height="2" rx="1"/></g></svg></a>
								<div>
									<h6 class="mb-1">Chat List</h6>
									<p class="mb-0">Show All</p>
								</div>
								<a href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect x="0" y="0" width="24" height="24"/><circle fill="#000000" cx="5" cy="12" r="2"/><circle fill="#000000" cx="12" cy="12" r="2"/><circle fill="#000000" cx="19" cy="12" r="2"/></g></svg></a>
							</div>
							<div class="card-body contacts_body p-0 dz-scroll  " id="DZ_W_Contacts_Body">
								<ul class="contacts">
									<li class="name-first-letter">A</li>
									<li class="active dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon"></span>
											</div>
											<div class="user_info">
												<span>Archie Parker</span>
												<p>Kalid is online</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Alfie Mason</span>
												<p>Taherah left 7 mins ago</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/3.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon"></span>
											</div>
											<div class="user_info">
												<span>AharlieKane</span>
												<p>Sami is online</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/4.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Athan Jacoby</span>
												<p>Nargis left 30 mins ago</p>
											</div>
										</div>
									</li>
									<li class="name-first-letter">B</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/5.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Bashid Samim</span>
												<p>Rashid left 50 mins ago</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon"></span>
											</div>
											<div class="user_info">
												<span>Breddie Ronan</span>
												<p>Kalid is online</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Ceorge Carson</span>
												<p>Taherah left 7 mins ago</p>
											</div>
										</div>
									</li>
									<li class="name-first-letter">D</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/3.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon"></span>
											</div>
											<div class="user_info">
												<span>Darry Parker</span>
												<p>Sami is online</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/4.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Denry Hunter</span>
												<p>Nargis left 30 mins ago</p>
											</div>
										</div>
									</li>
									<li class="name-first-letter">J</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/5.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Jack Ronan</span>
												<p>Rashid left 50 mins ago</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon"></span>
											</div>
											<div class="user_info">
												<span>Jacob Tucker</span>
												<p>Kalid is online</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>James Logan</span>
												<p>Taherah left 7 mins ago</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/3.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon"></span>
											</div>
											<div class="user_info">
												<span>Joshua Weston</span>
												<p>Sami is online</p>
											</div>
										</div>
									</li>
									<li class="name-first-letter">O</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/4.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Oliver Acker</span>
												<p>Nargis left 30 mins ago</p>
											</div>
										</div>
									</li>
									<li class="dz-chat-user">
										<div class="d-flex bd-highlight">
											<div class="img_cont">
												<img src="frontend/images/avatar/5.jpg" class="rounded-circle user_img" alt="">
												<span class="online_icon offline"></span>
											</div>
											<div class="user_info">
												<span>Oscar Weston</span>
												<p>Rashid left 50 mins ago</p>
											</div>
										</div>
									</li>
								</ul>
							</div>
						</div>
						<div class="card chat dz-chat-history-box d-none">
							<div class="card-header chat-list-header text-center">
								<a href="javascript:void(0);" class="dz-chat-history-back">
									<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><polygon points="0 0 24 0 24 24 0 24"/><rect fill="#000000" opacity="0.3" transform="translate(15.000000, 12.000000) scale(-1, 1) rotate(-90.000000) translate(-15.000000, -12.000000) " x="14" y="7" width="2" height="10" rx="1"/><path d="M3.7071045,15.7071045 C3.3165802,16.0976288 2.68341522,16.0976288 2.29289093,15.7071045 C1.90236664,15.3165802 1.90236664,14.6834152 2.29289093,14.2928909 L8.29289093,8.29289093 C8.67146987,7.914312 9.28105631,7.90106637 9.67572234,8.26284357 L15.6757223,13.7628436 C16.0828413,14.136036 16.1103443,14.7686034 15.7371519,15.1757223 C15.3639594,15.5828413 14.7313921,15.6103443 14.3242731,15.2371519 L9.03007346,10.3841355 L3.7071045,15.7071045 Z" fill="#000000" fill-rule="nonzero" transform="translate(9.000001, 11.999997) scale(-1, -1) rotate(90.000000) translate(-9.000001, -11.999997) "/></g></svg>
								</a>
								<div>
									<h6 class="mb-1">Chat with Khelesh</h6>
									<p class="mb-0 text-success">Online</p>
								</div>							
								<div class="dropdown">
									<a href="javascript:void(0);" data-bs-toggle="dropdown" aria-expanded="false"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect x="0" y="0" width="24" height="24"/><circle fill="#000000" cx="5" cy="12" r="2"/><circle fill="#000000" cx="12" cy="12" r="2"/><circle fill="#000000" cx="19" cy="12" r="2"/></g></svg></a>
									<ul class="dropdown-menu dropdown-menu-right">
										<li class="dropdown-item"><i class="fa fa-user-circle text-primary me-2"></i> View profile</li>
										<li class="dropdown-item"><i class="fa fa-users text-primary me-2"></i> Add to close friends</li>
										<li class="dropdown-item"><i class="fa fa-plus text-primary me-2"></i> Add to group</li>
										<li class="dropdown-item"><i class="fa fa-ban text-primary me-2"></i> Block</li>
									</ul>
								</div>
							</div>
							<div class="card-body msg_card_body dz-scroll" id="DZ_W_Contacts_Body3">
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										Hi, how are you samim?
										<span class="msg_time">8:40 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-end mb-4">
									<div class="msg_cotainer_send">
										Hi Khalid i am good tnx how about you?
										<span class="msg_time_send">8:55 AM, Today</span>
									</div>
									<div class="img_cont_msg">
								<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										I am good too, thank you for your chat template
										<span class="msg_time">9:00 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-end mb-4">
									<div class="msg_cotainer_send">
										You are welcome
										<span class="msg_time_send">9:05 AM, Today</span>
									</div>
									<div class="img_cont_msg">
								<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										I am looking for your next templates
										<span class="msg_time">9:07 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-end mb-4">
									<div class="msg_cotainer_send">
										Ok, thank you have a good day
										<span class="msg_time_send">9:10 AM, Today</span>
									</div>
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										Bye, see you
										<span class="msg_time">9:12 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										Hi, how are you samim?
										<span class="msg_time">8:40 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-end mb-4">
									<div class="msg_cotainer_send">
										Hi Khalid i am good tnx how about you?
										<span class="msg_time_send">8:55 AM, Today</span>
									</div>
									<div class="img_cont_msg">
								<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										I am good too, thank you for your chat template
										<span class="msg_time">9:00 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-end mb-4">
									<div class="msg_cotainer_send">
										You are welcome
										<span class="msg_time_send">9:05 AM, Today</span>
									</div>
									<div class="img_cont_msg">
								<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										I am looking for your next templates
										<span class="msg_time">9:07 AM, Today</span>
									</div>
								</div>
								<div class="d-flex justify-content-end mb-4">
									<div class="msg_cotainer_send">
										Ok, thank you have a good day
										<span class="msg_time_send">9:10 AM, Today</span>
									</div>
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/2.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
								</div>
								<div class="d-flex justify-content-start mb-4">
									<div class="img_cont_msg">
										<img src="frontend/images/avatar/1.jpg" class="rounded-circle user_img_msg" alt="">
									</div>
									<div class="msg_cotainer">
										Bye, see you
										<span class="msg_time">9:12 AM, Today</span>
									</div>
								</div>
							</div>
							<div class="card-footer type_msg">
								<div class="input-group">
									<textarea class="form-control" placeholder="Type your message..."></textarea>
									<div class="input-group-append">
										<button type="button" class="btn btn-primary"><i class="fa fa-location-arrow"></i></button>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="tab-pane fade" id="alerts" role="tabpanel">
						<div class="card mb-sm-3 mb-md-0 contacts_card">
							<div class="card-header chat-list-header text-center">
								<a href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect x="0" y="0" width="24" height="24"/><circle fill="#000000" cx="5" cy="12" r="2"/><circle fill="#000000" cx="12" cy="12" r="2"/><circle fill="#000000" cx="19" cy="12" r="2"/></g></svg></a>
								<div>
									<h6 class="mb-1">Notications</h6>
									<p class="mb-0">Show All</p>
								</div>
								<a href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect x="0" y="0" width="24" height="24"/><path d="M14.2928932,16.7071068 C13.9023689,16.3165825 13.9023689,15.6834175 14.2928932,15.2928932 C14.6834175,14.9023689 15.3165825,14.9023689 15.7071068,15.2928932 L19.7071068,19.2928932 C20.0976311,19.6834175 20.0976311,20.3165825 19.7071068,20.7071068 C19.3165825,21.0976311 18.6834175,21.0976311 18.2928932,20.7071068 L14.2928932,16.7071068 Z" fill="#000000" fill-rule="nonzero" opacity="0.3"/><path d="M11,16 C13.7614237,16 16,13.7614237 16,11 C16,8.23857625 13.7614237,6 11,6 C8.23857625,6 6,8.23857625 6,11 C6,13.7614237 8.23857625,16 11,16 Z M11,18 C7.13400675,18 4,14.8659932 4,11 C4,7.13400675 7.13400675,4 11,4 C14.8659932,4 18,7.13400675 18,11 C18,14.8659932 14.8659932,18 11,18 Z" fill="#000000" fill-rule="nonzero"/></g></svg></a>
							</div>
							<div class="card-body contacts_body p-0 dz-scroll" id="DZ_W_Contacts_Body1">
								<ul class="contacts">
									<li class="name-first-letter">SEVER STATUS</li>
									<li class="active">
										<div class="d-flex bd-highlight">
											<div class="img_cont primary">KK</div>
											<div class="user_info">
												<span>David Nester Birthday</span>
												<p class="text-primary">Today</p>
											</div>
										</div>
									</li>
									<li class="name-first-letter">SOCIAL</li>
									<li>
										<div class="d-flex bd-highlight">
											<div class="img_cont success">RU<i class="icon fa-birthday-cake"></i></div>
											<div class="user_info">
												<span>Perfection Simplified</span>
												<p>Jame Smith commented on your status</p>
											</div>
										</div>
									</li>
									<li class="name-first-letter">SEVER STATUS</li>
									<li>
										<div class="d-flex bd-highlight">
											<div class="img_cont primary">AU<i class="icon fa fa-user-plus"></i></div>
											<div class="user_info">
												<span>AharlieKane</span>
												<p>Sami is online</p>
											</div>
										</div>
									</li>
									<li>
										<div class="d-flex bd-highlight">
											<div class="img_cont info">MO<i class="icon fa fa-user-plus"></i></div>
											<div class="user_info">
												<span>Athan Jacoby</span>
												<p>Nargis left 30 mins ago</p>
											</div>
										</div>
									</li>
								</ul>
							</div>
							<div class="card-footer"></div>
						</div>
					</div>
					<div class="tab-pane fade" id="notes">
						<div class="card mb-sm-3 mb-md-0 note_card">
							<div class="card-header chat-list-header text-center">
								<a href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect fill="#000000" x="4" y="11" width="16" height="2" rx="1"/><rect fill="#000000" opacity="0.3" transform="translate(12.000000, 12.000000) rotate(-270.000000) translate(-12.000000, -12.000000) " x="4" y="11" width="16" height="2" rx="1"/></g></svg></a>
								<div>
									<h6 class="mb-1">Notes</h6>
									<p class="mb-0">Add New Nots</p>
								</div>
								<a href="javascript:void(0);"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18px" height="18px" viewBox="0 0 24 24" version="1.1"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><rect x="0" y="0" width="24" height="24"/><path d="M14.2928932,16.7071068 C13.9023689,16.3165825 13.9023689,15.6834175 14.2928932,15.2928932 C14.6834175,14.9023689 15.3165825,14.9023689 15.7071068,15.2928932 L19.7071068,19.2928932 C20.0976311,19.6834175 20.0976311,20.3165825 19.7071068,20.7071068 C19.3165825,21.0976311 18.6834175,21.0976311 18.2928932,20.7071068 L14.2928932,16.7071068 Z" fill="#000000" fill-rule="nonzero" opacity="0.3"/><path d="M11,16 C13.7614237,16 16,13.7614237 16,11 C16,8.23857625 13.7614237,6 11,6 C8.23857625,6 6,8.23857625 6,11 C6,13.7614237 8.23857625,16 11,16 Z M11,18 C7.13400675,18 4,14.8659932 4,11 C4,7.13400675 7.13400675,4 11,4 C14.8659932,4 18,7.13400675 18,11 C18,14.8659932 14.8659932,18 11,18 Z" fill="#000000" fill-rule="nonzero"/></g></svg></a>
							</div>
							<div class="card-body contacts_body p-0 dz-scroll" id="DZ_W_Contacts_Body2">
								<ul class="contacts">
									<li class="active">
										<div class="d-flex bd-highlight">
											<div class="user_info">
												<span>New order placed..</span>
												<p>10 Aug 2020</p>
											</div>
											<div class="ms-auto">
												<a href="javascript:void(0);" class="btn btn-primary btn-xs sharp me-1"><i class="fa fa-pencil"></i></a>
												<a href="javascript:void(0);" class="btn btn-danger btn-xs sharp"><i class="fa fa-trash"></i></a>
											</div>
										</div>
									</li>
									<li>
										<div class="d-flex bd-highlight">
											<div class="user_info">
												<span>Youtube, a video-sharing website..</span>
												<p>10 Aug 2020</p>
											</div>
											<div class="ms-auto">
												<a href="javascript:void(0);" class="btn btn-primary btn-xs sharp me-1"><i class="fa fa-pencil"></i></a>
												<a href="javascript:void(0);" class="btn btn-danger btn-xs sharp"><i class="fa fa-trash"></i></a>
											</div>
										</div>
									</li>
									<li>
										<div class="d-flex bd-highlight">
											<div class="user_info">
												<span>john just buy your product..</span>
												<p>10 Aug 2020</p>
											</div>
											<div class="ms-auto">
												<a href="javascript:void(0);" class="btn btn-primary btn-xs sharp me-1"><i class="fa fa-pencil"></i></a>
												<a href="javascript:void(0);" class="btn btn-danger btn-xs sharp"><i class="fa fa-trash"></i></a>
											</div>
										</div>
									</li>
									<li>
										<div class="d-flex bd-highlight">
											<div class="user_info">
												<span>Athan Jacoby</span>
												<p>10 Aug 2020</p>
											</div>
											<div class="ms-auto">
												<a href="javascript:void(0);" class="btn btn-primary btn-xs sharp me-1"><i class="fa fa-pencil"></i></a>
												<a href="javascript:void(0);" class="btn btn-danger btn-xs sharp"><i class="fa fa-trash"></i></a>
											</div>
										</div>
									</li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	
	    <div class="header">
		<div class="header-content">
			<nav class="navbar navbar-expand">
				<div class="collapse navbar-collapse justify-content-between">
					<div class="header-left">
						<div class="nav-header">
							<a href="index.html" class="brand-logo show-nav">
								<img src="frontend/images/logo/Logo_FBS-Wide.png" alt="image" class="pt-3 me-3 rounded"
									width="225">
							</a>
						
							<a href="index.html" class="brand-logo mobile">
								<img src="frontend/images/logo/Logo_FBS.png" alt="image" class="me-3 rounded" width="57">
							</a>

						</div>
					</div>

					<ul class="navbar-nav header-right">
						<li class="nav-item dropdown notification_dropdown">
							<a class="nav-link  ai-icon" href="javascript:;" role="button"
								data-bs-toggle="dropdown">
								<svg width="25" height="25" viewBox="0 0 26 26" fill="none"
									xmlns="http://www.w3.org/2000/svg">
									<path
										d="M21.75 14.8385V12.0463C21.7471 9.88552 20.9385 7.80353 19.4821 6.20735C18.0258 4.61116 16.0264 3.61555 13.875 3.41516V1.625C13.875 1.39294 13.7828 1.17038 13.6187 1.00628C13.4546 0.842187 13.2321 0.75 13 0.75C12.7679 0.75 12.5454 0.842187 12.3813 1.00628C12.2172 1.17038 12.125 1.39294 12.125 1.625V3.41534C9.97361 3.61572 7.97429 4.61131 6.51794 6.20746C5.06159 7.80361 4.25291 9.88555 4.25 12.0463V14.8383C3.26257 15.0412 2.37529 15.5784 1.73774 16.3593C1.10019 17.1401 0.751339 18.1169 0.75 19.125C0.750764 19.821 1.02757 20.4882 1.51969 20.9803C2.01181 21.4724 2.67904 21.7492 3.375 21.75H8.71346C8.91521 22.738 9.45205 23.6259 10.2331 24.2636C11.0142 24.9013 11.9916 25.2497 13 25.2497C14.0084 25.2497 14.9858 24.9013 15.7669 24.2636C16.548 23.6259 17.0848 22.738 17.2865 21.75H22.625C23.321 21.7492 23.9882 21.4724 24.4803 20.9803C24.9724 20.4882 25.2492 19.821 25.25 19.125C25.2486 18.117 24.8998 17.1402 24.2622 16.3594C23.6247 15.5786 22.7374 15.0414 21.75 14.8385ZM6 12.0463C6.00232 10.2113 6.73226 8.45223 8.02974 7.15474C9.32723 5.85726 11.0863 5.12732 12.9212 5.125H13.0788C14.9137 5.12732 16.6728 5.85726 17.9703 7.15474C19.2677 8.45223 19.9977 10.2113 20 12.0463V14.75H6V12.0463ZM13 23.5C12.4589 23.4983 11.9316 23.3292 11.4905 23.0159C11.0493 22.7026 10.716 22.2604 10.5363 21.75H15.4637C15.284 22.2604 14.9507 22.7026 14.5095 23.0159C14.0684 23.3292 13.5411 23.4983 13 23.5ZM22.625 20H3.375C3.14298 19.9999 2.9205 19.9076 2.75644 19.7436C2.59237 19.5795 2.50014 19.357 2.5 19.125C2.50076 18.429 2.77757 17.7618 3.26969 17.2697C3.76181 16.7776 4.42904 16.5008 5.125 16.5H20.875C21.571 16.5008 22.2382 16.7776 22.7303 17.2697C23.2224 17.7618 23.4992 18.429 23.5 19.125C23.4999 19.357 23.4076 19.5795 23.2436 19.7436C23.0795 19.9076 22.857 19.9999 22.625 20Z"
										fill="#36C95F"></path>
								</svg>
								<span class="badge light text-white bg-primary">12</span>
							</a>
							<div class="dropdown-menu dropdown-menu-end">
								<div id="DZ_W_Notification1" class="widget-media dz-scroll p-3 height380">
									<ul class="timeline">
										<li>
											<div class="timeline-panel">
												<div class="media me-2">
													<img alt="image" width="50" src="frontend/images/avatar/1.jpg">
												</div>
												<div class="media-body">
													<h6 class="mb-1">Dr sultads Send you Photo</h6>
													<small class="d-block">29 July 2020 - 02:26 PM</small>
												</div>
											</div>
										</li>
										<li>
											<div class="timeline-panel">
												<div class="media me-2 media-info">
													KG
												</div>
												<div class="media-body">
													<h6 class="mb-1">Resport created successfully</h6>
													<small class="d-block">29 July 2020 - 02:26 PM</small>
												</div>
											</div>
										</li>
										<li>
											<div class="timeline-panel">
												<div class="media me-2 media-success">
													<i class="fa fa-home"></i>
												</div>
												<div class="media-body">
													<h6 class="mb-1">Reminder : Treatment Time!</h6>
													<small class="d-block">29 July 2020 - 02:26 PM</small>
												</div>
											</div>
										</li>
										<li>
											<div class="timeline-panel">
												<div class="media me-2">
													<img alt="image" width="50" src="frontend/images/avatar/1.jpg">
												</div>
												<div class="media-body">
													<h6 class="mb-1">Dr sultads Send you Photo</h6>
													<small class="d-block">29 July 2020 - 02:26 PM</small>
												</div>
											</div>
										</li>
										<li>
											<div class="timeline-panel">
												<div class="media me-2 media-danger">
													KG
												</div>
												<div class="media-body">
													<h6 class="mb-1">Resport created successfully</h6>
													<small class="d-block">29 July 2020 - 02:26 PM</small>
												</div>
											</div>
										</li>
										<li>
											<div class="timeline-panel">
												<div class="media me-2 media-primary">
													<i class="fa fa-home"></i>
												</div>
												<div class="media-body">
													<h6 class="mb-1">Reminder : Treatment Time!</h6>
													<small class="d-block">29 July 2020 - 02:26 PM</small>
												</div>
											</div>
										</li>
									</ul>
								</div>
								<a class="all-notification" href="javascript:;">See all notifications <i
										class="ti-arrow-right"></i></a>
							</div>
						</li>
						<li class="nav-item dropdown notification_dropdown">
							<a class="nav-link bell bell-link ai-icon" href="javascript:;">
								<svg width="23" height="28" viewBox="0 0 23 22" fill="none"
									xmlns="http://www.w3.org/2000/svg">
									<path
										d="M20.4604 0.848846H3.31682C2.64742 0.849582 2.00565 1.11583 1.53231 1.58916C1.05897 2.0625 0.792727 2.70427 0.791992 3.37367V15.1562C0.792727 15.8256 1.05897 16.4674 1.53231 16.9407C2.00565 17.414 2.64742 17.6803 3.31682 17.681C3.53999 17.6812 3.75398 17.7699 3.91178 17.9277C4.06958 18.0855 4.15829 18.2995 4.15843 18.5226V20.3168C4.15843 20.6214 4.24112 20.9204 4.39768 21.1817C4.55423 21.4431 4.77879 21.6571 5.04741 21.8008C5.31602 21.9446 5.61861 22.0127 5.92292 21.998C6.22723 21.9833 6.52183 21.8863 6.77533 21.7173L12.6173 17.8224C12.7554 17.7299 12.9179 17.6807 13.0841 17.681H17.187C17.7383 17.68 18.2742 17.4993 18.7136 17.1664C19.1531 16.8334 19.472 16.3664 19.6222 15.8359L22.8965 4.05007C22.9998 3.67478 23.0152 3.28071 22.9413 2.89853C22.8674 2.51634 22.7064 2.15636 22.4707 1.8466C22.2349 1.53684 21.9309 1.28565 21.5822 1.1126C21.2336 0.93954 20.8497 0.849282 20.4604 0.848846ZM21.2732 3.60301L18.0005 15.3847C17.9499 15.5614 17.8432 15.7168 17.6964 15.8274C17.5496 15.938 17.3708 15.9979 17.187 15.9978H13.0841C12.5855 15.9972 12.098 16.1448 11.6836 16.4219L5.84165 20.3168V18.5226C5.84091 17.8532 5.57467 17.2115 5.10133 16.7381C4.62799 16.2648 3.98622 15.9985 3.31682 15.9978C3.09365 15.9977 2.87966 15.909 2.72186 15.7512C2.56406 15.5934 2.47534 15.3794 2.47521 15.1562V3.37367C2.47534 3.15051 2.56406 2.93652 2.72186 2.77871C2.87966 2.62091 3.09365 2.5322 3.31682 2.53206H20.4604C20.5905 2.53239 20.7187 2.56274 20.8352 2.62073C20.9516 2.67872 21.0531 2.7628 21.1318 2.86643C21.2104 2.97005 21.2641 3.09042 21.2886 3.21818C21.3132 3.34594 21.3079 3.47763 21.2732 3.60301Z"
										fill="#36C95F"></path>
									<path
										d="M5.84161 8.42333H10.0497C10.2729 8.42333 10.4869 8.33466 10.6448 8.17683C10.8026 8.019 10.8913 7.80493 10.8913 7.58172C10.8913 7.35851 10.8026 7.14445 10.6448 6.98661C10.4869 6.82878 10.2729 6.74011 10.0497 6.74011H5.84161C5.6184 6.74011 5.40433 6.82878 5.2465 6.98661C5.08867 7.14445 5 7.35851 5 7.58172C5 7.80493 5.08867 8.019 5.2465 8.17683C5.40433 8.33466 5.6184 8.42333 5.84161 8.42333Z"
										fill="#36C95F"></path>
									<path
										d="M13.4161 10.1065H5.84161C5.6184 10.1065 5.40433 10.1952 5.2465 10.353C5.08867 10.5109 5 10.7249 5 10.9481C5 11.1714 5.08867 11.3854 5.2465 11.5433C5.40433 11.7011 5.6184 11.7898 5.84161 11.7898H13.4161C13.6393 11.7898 13.8534 11.7011 14.0112 11.5433C14.169 11.3854 14.2577 11.1714 14.2577 10.9481C14.2577 10.7249 14.169 10.5109 14.0112 10.353C13.8534 10.1952 13.6393 10.1065 13.4161 10.1065Z"
										fill="#36C95F"></path>
								</svg>
								<span class="badge light text-white bg-primary">5</span>
							</a>
						</li>
						<li class="nav-item dropdown notification_dropdown">
							<a class="nav-link ai-icon" href="javascript:;" role="button" data-bs-toggle="dropdown">
								<svg class="svg-multi-color" width="25" height="25" viewBox="0 0 26 26" fill="none"
									xmlns="http://www.w3.org/2000/svg">
									<path
										d="M22.625 5.125H21.75V1.625C21.75 1.47262 21.7102 1.32289 21.6345 1.19062C21.5589 1.05835 21.45 0.948128 21.3186 0.870868C21.1873 0.793609 21.0381 0.751989 20.8857 0.750126C20.7333 0.748264 20.5831 0.786224 20.4499 0.86025L13 4.99909L5.55007 0.86025C5.41688 0.786224 5.26667 0.748264 5.11431 0.750126C4.96194 0.751989 4.8127 0.793609 4.68136 0.870868C4.55002 0.948128 4.44113 1.05835 4.36547 1.19062C4.28981 1.32289 4.25001 1.47262 4.25 1.625V5.125H3.375C2.67904 5.12576 2.01181 5.40257 1.51969 5.89469C1.02757 6.3868 0.750764 7.05404 0.75 7.75V10.375C0.750764 11.071 1.02757 11.7382 1.51969 12.2303C2.01181 12.7224 2.67904 12.9992 3.375 13H4.25V22.625C4.25076 23.321 4.52757 23.9882 5.01969 24.4803C5.51181 24.9724 6.17904 25.2492 6.875 25.25H19.125C19.821 25.2492 20.4882 24.9724 20.9803 24.4803C21.4724 23.9882 21.7492 23.321 21.75 22.625V13H22.625C23.321 12.9992 23.9882 12.7224 24.4803 12.2303C24.9724 11.7382 25.2492 11.071 25.25 10.375V7.75C25.2492 7.05404 24.9724 6.3868 24.4803 5.89469C23.9882 5.40257 23.321 5.12576 22.625 5.125ZM20 5.125H16.3769L20 3.1125V5.125ZM6 3.1125L9.62311 5.125H6V3.1125ZM6 22.625V13H12.125V23.5H6.875C6.64303 23.4997 6.42064 23.4074 6.25661 23.2434C6.09258 23.0793 6.0003 22.857 6 22.625ZM20 22.625C19.9997 22.857 19.9074 23.0793 19.7434 23.2434C19.5794 23.4074 19.357 23.4997 19.125 23.5H13.875V13H20V22.625ZM23.5 10.375C23.4997 10.607 23.4074 10.8294 23.2434 10.9934C23.0794 11.1574 22.857 11.2497 22.625 11.25H3.375C3.14303 11.2497 2.92064 11.1574 2.75661 10.9934C2.59258 10.8294 2.5003 10.607 2.5 10.375V7.75C2.5003 7.51803 2.59258 7.29564 2.75661 7.13161C2.92064 6.96758 3.14303 6.8753 3.375 6.875H22.625C22.857 6.8753 23.0794 6.96758 23.2434 7.13161C23.4074 7.29564 23.4997 7.51803 23.5 7.75V10.375Z"
										fill="#3E4954"></path>
								</svg>
								<span class="badge light text-white bg-dark">2</span>
							</a>
							<div class="dropdown-menu dropdown-menu-end p-0">
								<div id="DZ_W_Gifts" class="widget-timeline p-3 dz-scroll style-1 height300">
									<ul class="timeline">
										<li>
											<div class="timeline-badge primary"></div>
											<a class="timeline-panel text-muted" href="javascript:;">
												<span>10 minutes ago</span>
												<h6 class="mb-0">Youtube, a video-sharing website, goes live <strong
														class="text-primary">$500</strong>.</h6>
											</a>
										</li>
										<li>
											<div class="timeline-badge info">
											</div>
											<a class="timeline-panel text-muted" href="javascript:;">
												<span>20 minutes ago</span>
												<h6 class="mb-0">New order placed <strong
														class="text-info">#XF-2356.</strong></h6>
												<p class="mb-0">Quisque a consequat ante Sit amet magna at
													volutapt...</p>
											</a>
										</li>
										<li>
											<div class="timeline-badge danger">
											</div>
											<a class="timeline-panel text-muted" href="javascript:;">
												<span>30 minutes ago</span>
												<h6 class="mb-0">john just buy your product <strong
														class="text-warning">Sell $250</strong></h6>
											</a>
										</li>
										<li>
											<div class="timeline-badge success">
											</div>
											<a class="timeline-panel text-muted" href="javascript:;">
												<span>15 minutes ago</span>
												<h6 class="mb-0">StumbleUpon is acquired by eBay. </h6>
											</a>
										</li>
										<li>
											<div class="timeline-badge warning">
											</div>
											<a class="timeline-panel text-muted" href="javascript:;">
												<span>20 minutes ago</span>
												<h6 class="mb-0">Mashable, a news website and blog, goes live.</h6>
											</a>
										</li>
										<li>
											<div class="timeline-badge dark">
											</div>
											<a class="timeline-panel text-muted" href="javascript:;">
												<span>20 minutes ago</span>
												<h6 class="mb-0">Mashable, a news website and blog, goes live.</h6>
											</a>
										</li>
									</ul>
								</div>
							</div>
						</li>
						<li class="nav-item dropdown notification_dropdown">
							<a class="nav-link bell dz-theme-mode" href="javascript:void(0);">
								<i id="icon-light" class="fas fa-sun"></i>
								<i id="icon-dark" class="fas fa-moon"></i>

							</a>
						</li>
						<li class="nav-item dropdown header-profile">
							<a class="nav-link" href="javascript:;" role="button" data-bs-toggle="dropdown">
								<img src="frontend/images/profile/12.png" width="20" alt="">
								<div class="header-info">
									<span>Hello,<strong> Roberto</strong></span>
								</div>
							</a>
							<div class="dropdown-menu dropdown-menu-end">
								<a href="fbs-triumph-dashboard_app-profile.html" class="dropdown-item ai-icon">
									<svg id="icon-user1" xmlns="http://www.w3.org/2000/svg" class="text-primary"
										width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor"
										stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
										<path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"></path>
										<circle cx="12" cy="7" r="4"></circle>
									</svg>
									<span class="ms-2">Profile </span>
								</a>

								<a href="fbs-triumph-dashboard_login.html" class="dropdown-item ai-icon">
									<svg id="icon-logout" xmlns="http://www.w3.org/2000/svg" class="text-danger"
										width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor"
										stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
										<path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"></path>
										<polyline points="16 17 21 12 16 7"></polyline>
										<line x1="21" y1="12" x2="9" y2="12"></line>
									</svg>
									<span class="ms-2">Logout </span>
								</a>
							</div>
						</li>
					</ul>
				</div>
			</nav>
		</div>
	    </div>

    
	
       <div class="content-body">
            <!-- row -->
			<div class="container-fluid">

				<div class="form-head d-flex mb-3 mb-md-4 align-items-start">
					<div class="me-auto d-none d-lg-block">
					<h3 class="text-black font-w600">Hi, Roberto</h3>
					<p class="mb-0 fs-18">Welcome to Trading Triumph!</p>
				    </div>
				</div>

				<div class="row">
				    <div class="col-lg-12">
					    <div class="profile card card-body px-3 pb-3 pt-3 pb-0">

						<div class="row justify-content-between flex-column flex-lg-row align-items-start align-items-lg-center gap-4 gap-lg-0">
							<div class="hero-content col-12 d-flex flex-column justify-content-start mt-lg-0">

								<div class="card-header border-0 pt-1 pb-3">
									<h3 class="fs-20 mb-0 text-black">Latest Promotions</h3>
								</div>
								<div id="carouselExampleIndicators" class="carousel slide pb-3" data-bs-ride="carousel">
									<div class="carousel-indicators">
										<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="" aria-label="Slide 1"></button>
										<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2" class="active" aria-current="true"></button>
										<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3" class=""></button>
									</div>
									<div class="carousel-inner swiper-img">
										<div class="carousel-item active carousel-item-start" data-bs-interval="1000">
											<img src="frontend/images//banners/banner-1.jpg" class="d-block w-100">
										</div>
										<div class="carousel-item carousel-item-next carousel-item-start">
											<img src="frontend/images//banners/banner-2.jpg" class="d-block w-100">
										</div>
										<div class="carousel-item">
											<img src="frontend/images//banners/banner-1.jpg" class="d-block w-100">
										</div>
									</div>
									<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
										<span class="carousel-control-prev-icon" aria-hidden="true"></span>
										<span class="visually-hidden">Previous</span>
									</button>
									<button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
										<span class="carousel-control-next-icon" aria-hidden="true"></span>
										<span class="visually-hidden">Next</span>
									</button>
								</div>
							</div>
						</div>
					    </div>
				    </div>
			    </div>
                
				<div class="row">
                    <div class="col-xl-4">
					<div class="row h-100">
						<div class="col-xl-12">
							<div class="card">
								<div class="card-body d-flex">
									<div class="profile-info">
										<div class="profile-photo">
											<img src="frontend/images/profile/12.png" class="img-fluid rounded-circle" alt="">
										</div>
										<div class="profile-details">
											<div class="profile-name px-3 pt-2">
												<h4 class="text-primary mb-0 pb-2">Roberto</h4>


												<h4 class="text-muted mb-10">info@example.com</h4>
									
												<p class="text-start" style="font-size: 10px;">Update every friday before midnight</p>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
				    </div>
                <div class="col-xl-8">
                    <div class="card">
                    <div class="card-header">
							<h4 class="card-title">Lots traded and deposit will be update every Friday before midninght</h4>
						</div>
                        <div class="row" style=" padding: 20px 20px 0px 20px;">
							<div class="col-xl-6 col-md-6">
								<div class="card transaction text-white bg-success">
									<div class="card-body">
										<div class="media align-items-center">
											<div class="media-body">
												<h2 class="mb-1">Deposits</h2>
												<div class="d-flex flex-wrap">
													<h2 class="fs-40 font-w600 text-white mb-0 me-3">$1000</h2>

												</div>
											</div>
											<span class="border rounded-circle p-4">
												<svg xmlns="http://www.w3.org/2000/svg" width="34" height="34" fill="currentColor" class="bi bi-cash-coin" viewBox="0 0 16 16">
													<path fill-rule="evenodd" d="M11 15a4 4 0 1 0 0-8 4 4 0 0 0 0 8zm5-4a5 5 0 1 1-10 0 5 5 0 0 1 10 0z">
													</path>
													<path d="M9.438 11.944c.047.596.518 1.06 1.363 1.116v.44h.375v-.443c.875-.061 1.386-.529 1.386-1.207 0-.618-.39-.936-1.09-1.1l-.296-.07v-1.2c.376.043.614.248.671.532h.658c-.047-.575-.54-1.024-1.329-1.073V8.5h-.375v.45c-.747.073-1.255.522-1.255 1.158 0 .562.378.92 1.007 1.066l.248.061v1.272c-.384-.058-.639-.27-.696-.563h-.668zm1.36-1.354c-.369-.085-.569-.26-.569-.522 0-.294.216-.514.572-.578v1.1h-.003zm.432.746c.449.104.655.272.655.569 0 .339-.257.571-.709.614v-1.195l.054.012z">
													</path>
													<path 	d="M1 0a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h4.083c.058-.344.145-.678.258-1H3a2 2 0 0 0-2-2V3a2 2 0 0 0 2-2h10a2 2 0 0 0 2 2v3.528c.38.34.717.728 1 1.154V1a1 1 0 0 0-1-1H1z">
													</path>
													<path d="M9.998 5.083 10 5a2 2 0 1 0-3.132 1.65 5.982 5.982 0 0 1 3.13-1.567z">
													</path>
												</svg>
											</span>
										</div>
									</div>
								</div>
							</div>
							<div class="col-xl-6 col-md-6">
								<div class="card transaction text-white bg-success">
									<div class="card-body">
										<div class="media align-items-center">
											<div class="media-body">
												<h2 class="mb-1">Lots Traded</h2>
												<div class="d-flex flex-wrap">
													<h2 class="fs-40 font-w600 text-white mb-0 me-3">150</h2>

												</div>
											</div>
											<span class="border rounded-circle p-4">
												<svg xmlns="http://www.w3.org/2000/svg" width="34" height="34" fill="currentColor" class="bi bi-coin" viewBox="0 0 16 16">
													<path d="M5.5 9.511c.076.954.83 1.697 2.182 1.785V12h.6v-.709c1.4-.098 2.218-.846 2.218-1.932 0-.987-.626-1.496-1.745-1.76l-.473-.112V5.57c.6.068.982.396 1.074.85h1.052c-.076-.919-.864-1.638-2.126-1.716V4h-.6v.719c-1.195.117-2.01.836-2.01 1.853 0 .9.606 1.472 1.613 1.707l.397.098v2.034c-.615-.093-1.022-.43-1.114-.9H5.5zm2.177-2.166c-.59-.137-.91-.416-.91-.836 0-.47.345-.822.915-.925v1.76h-.005zm.692 1.193c.717.166 1.048.435 1.048.91 0 .542-.412.914-1.135.982V8.518l.087.02z">
													</path>
													<path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z">
													</path>
													<path d="M8 13.5a5.5 5.5 0 1 1 0-11 5.5 5.5 0 0 1 0 11zm0 .5A6 6 0 1 0 8 2a6 6 0 0 0 0 12z">
													</path>
												</svg>
											</span>
										</div>
									</div>
								</div>
							</div>
						</div>
                    </div>
                </div>

                </div>

<div class="row">
					<div class="col-xl-3 col-lg-12 col-xxl-3 col-sm-12">
						<div class="card">
							<div class="card-body  text-center ai-icon prize text-primary">
								<img src="frontend/images//Prize/prize-1.png" alt="" class="img-fluidmb-4 mb-4 w-100">
								<h4 class="my-2">Prize 1 : Giftset</h4>
								<p>Required:
									200$ Deposit 10 Lots</p>
								<button type="button" class="btn my-2 btn-primary btn-lg px-4" data-bs-toggle="modal"
									data-bs-target="#claimModal">
									Claim Prize
								</button>
							</div>
						</div>
					</div>

					<div class="col-xl-3 col-lg-12 col-xxl-3 col-sm-12">
						<div class="card ">
							<div class="card-body text-center ai-icon prize text-primary">
								<img src="frontend/images//Prize/prize-2.png" alt="" class="img-fluid mb-4 w-100">
								<h4 class="my-2">Prize 2 : Gift Voucher</h4>
								<p>Required:
									500$ Deposit 30 Lots</p>
								<button type="button" class="btn my-2 btn-primary btn-lg px-4" data-bs-toggle="modal"
									data-bs-target="#claimModal">
									Claim Prize
								</button>
							</div>
						</div>
					</div>
					<div class="col-xl-3 col-lg-12 col-xxl-3 col-sm-12">
						<div class="card">
							<div class="card-body text-center ai-icon prize text-primary">
								<img src="frontend/images//Prize/prize-3.png" alt="" class="img-fluid mb-4 w-100">
								<h4 class="my-2">Prize 3 : Samsung Phone</h4>
								<p>Required:
									1000$ Deposit 50 Lots</p>
								<button type="button" class="btn my-2 btn-primary btn-lg px-4" data-bs-toggle="modal"
									data-bs-target="#claimModal">
									Claim Prize
								</button>
							</div>
						</div>
					</div>
					<div class="col-xl-3 col-lg-12 col-xxl-3 col-sm-12">
						<div class="card">
							<div class="card-body text-center ai-icon prize text-primary">
								<img src="frontend/images//Prize/prize-4.png" alt="" class="img-fluid mb-4 w-100">
								<h4 class="my-2">Prize 4 : Apple Watch</h4>
								<p>Required:
									3000$ Deposit 150 Lots</p>
								<button type="button" class="btn my-2 btn-primary btn-lg px-4" data-bs-toggle="modal"
									data-bs-target="#claimModal">
									Claim Prize
								</button>
							</div>
						</div>
					</div>

				</div>
				<div class="row">
					<div class="col-lg-12">
                        <div class="card">
                            <div class="card-header">
                                <h4 class="card-title">Order List</h4>
                            </div>
                            <div class="card-body">
                                <div class="table-responsive">
                                    <table class="table table-responsive-sm">
                                        <thead>
                                            <tr>
                                                <th>#</th>
                                                <th>Prize</th>
                                                <th>Deposit</th>
                                                <th>Lot</th>
                                                <th>Date</th>
                                                <th>Status</th>
                                            </tr>
                                        </thead>
                                        <tbody>
                                            <tr>
                                                <th class="text-black">1</th>
                                                <td>Gift Voucher</td>
                                                <td>$500</td>
                                                <td class="color-primary">30</td>
                                                <td class="color-primary">15/08/2023</td>
                                                <td><span class="badge badge-primary">Order Received</span>
                                                </td>
                                            </tr>
                                            <tr>
												<th class="text-black">2</th>
												<td>Giftset</td>
												<td>$200</td>
												<td class="color-primary">10</td>
												<td class="color-primary">15/08/2023</td>
                                                <td><span class="badge badge-warning">Preparing</span>
												</td>
                                            </tr>
                                            <tr>
												<th class="text-black">3</th>
												<td>Samsung Phone</td>
												<td>$1000</td>
												<td class="color-primary">50</td>
												<td class="color-primary">15/08/2023</td>
                                                <td><span class="badge badge-danger">Out Deliver</span>
												</td>
                                            </tr>
                                            <tr>
												<th class="text-black">4</th>
												<td>Samsung Phone</td>
												<td>$1000</td>
												<td class="color-primary">50</td>
												<td class="color-primary">15/08/2023</td>
                                                <td><span class="badge badge-primary">Order Received</span>
                                                </td>
                                            </tr>
                                            <tr>
												<th class="text-black">5</th>
												<td>Apple Watch</td>
												<td>$3000</td>
												<td class="color-primary">150</td>
												<td class="color-primary">15/08/2023</td>
                                                <td><span class="badge badge-primary">Order Received</span>
                                                </td>
                                            </tr>
                                        </tbody>
                                    </table>
                                </div>
                            </div>
							<div class="card-footer">
							<nav>
								<ul class="pagination pagination-sm pagination-gutter justify-content-center">
									<li class="page-item page-indicator">
										<a class="page-link" href="javascript:void(0)">
											<i class="la la-angle-left"></i></a>
									</li>
									<li class="page-item active"><a class="page-link" href="javascript:void(0)">1</a>
									</li>
									<li class="page-item"><a class="page-link" href="javascript:void(0)">2</a></li>
									<li class="page-item"><a class="page-link" href="javascript:void(0)">3</a></li>
									<li class="page-item"><a class="page-link" href="javascript:void(0)">4</a></li>
									<li class="page-item page-indicator">
										<a class="page-link" href="javascript:void(0)">
											<i class="la la-angle-right"></i></a>
									</li>
								</ul>
							</nav>
						</div>
                        </div>
                    </div>

				</div>

            </div>
        </div>


<form>
	<div class="modal fade" id="claimModal" tabindex="-1" aria-labelledby="claimModalLabel" aria-hidden="true">
		<div class="modal-dialog modal-dialog-centered modal-lg">
			<div class="modal-content ">

				<div class="row">
					<div class="col-xl-12 col-lg-12 col-xxl-12 col-sm-12">
						<div class="">
							<div class="card-header">
								<h4 class="card-title">Fill the address form for deliver your prize</h4>
							</div>
							<div class="card-body">
								<div class="basic-form">


									<div class="row">
										<div class="mb-3 col-md-6">
											<label class="form-label">House/ Building number</label>
											<input type="text" class="form-control">
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
										</div>
										<div class="mb-3 col-md-6">
											<label class="form-label">Street, Road, Alley</label>
											<input type="text" class="form-control">
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
										</div>
										<div class="mb-3 col-md-6">
											<label class="form-label">Sub-District</label>
											<input type="text" class="form-control">
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
										</div>
										<div class="mb-3 col-md-6">
											<label>District</label>
											<input type="text" class="form-control">
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
										</div>
										<div class="mb-3 col-md-6">
											<label>Province</label>
											<input type="text" class="form-control">
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
										</div>
										<div class="mb-3 col-md-6">
											<label>Zip Code</label>
											<input type="number" class="form-control">
											<div data-lastpass-icon-root="true"
												style="position: relative !important; height: 0px !important; width: 0px !important; float: left !important;">
											</div>
										</div>
									</div>




								</div>
							</div>
							<div class="modal-footer">

								<button type="button" class="btn btn-outline-success" data-bs-dismiss="modal">
									Close
								</button>
								<button type="button" class="btn btn-primary" data-bs-toggle="modal"
									data-bs-target="#exampleModal">
									Submit
								</button>
							</div>
						</div>
					</div>





				</div>
			</div>
		</div>
	</div>
	</form>

<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
		<div class="modal-dialog modal-dialog-centered modal-size-40">
			<div class="modal-content py-4 ">

				<div class="modal-body d-flex flex-column align-items-center mt-3">
					<h2 class="modal-h2 font-Poppins text-center lh-sm">Your Prize is on the way! </h2>
					<h4 class="modal-h4 font-Poppins text-center">For futher request, Please contact our admin</h4>
					<a href="https://www.facebook.com/FBSThailand/" target="_blank" type="button"
						class="btn btn-success mt-4 px-3 py-1 font-Poppins">
						<img src="images/svg/fb.svg" alt="icon-facebook">&nbsp;
						Go to Facebook
					</a>
				</div>
				<div class="modal-footer gap-2 d-flex justify-content-center">
					<a url="#" type="button" class="btn btn-outline-success btn-sm py-1 px-4 font-Poppins"
						data-bs-dismiss="modal">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
							class="bi bi-grid" viewBox="0 0 16 16">
							<path
								d="M1 2.5A1.5 1.5 0 0 1 2.5 1h3A1.5 1.5 0 0 1 7 2.5v3A1.5 1.5 0 0 1 5.5 7h-3A1.5 1.5 0 0 1 1 5.5v-3zM2.5 2a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3zm6.5.5A1.5 1.5 0 0 1 10.5 1h3A1.5 1.5 0 0 1 15 2.5v3A1.5 1.5 0 0 1 13.5 7h-3A1.5 1.5 0 0 1 9 5.5v-3zm1.5-.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3zM1 10.5A1.5 1.5 0 0 1 2.5 9h3A1.5 1.5 0 0 1 7 10.5v3A1.5 1.5 0 0 1 5.5 15h-3A1.5 1.5 0 0 1 1 13.5v-3zm1.5-.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3zm6.5.5A1.5 1.5 0 0 1 10.5 9h3a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 13.5v-3zm1.5-.5a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5h-3z" />
						</svg>
						&nbsp;Back to Dashboard
					</a>
					<a href="https://fbs.com/" type="button" target="_blank"
						class="btn btn-outline-success btn-sm py-1 font-Poppins">
						<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
							class="bi bi-globe2" viewBox="0 0 16 16">
							<path
								d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm7.5-6.923c-.67.204-1.335.82-1.887 1.855-.143.268-.276.56-.395.872.705.157 1.472.257 2.282.287V1.077zM4.249 3.539c.142-.384.304-.744.481-1.078a6.7 6.7 0 0 1 .597-.933A7.01 7.01 0 0 0 3.051 3.05c.362.184.763.349 1.198.49zM3.509 7.5c.036-1.07.188-2.087.436-3.008a9.124 9.124 0 0 1-1.565-.667A6.964 6.964 0 0 0 1.018 7.5h2.49zm1.4-2.741a12.344 12.344 0 0 0-.4 2.741H7.5V5.091c-.91-.03-1.783-.145-2.591-.332zM8.5 5.09V7.5h2.99a12.342 12.342 0 0 0-.399-2.741c-.808.187-1.681.301-2.591.332zM4.51 8.5c.035.987.176 1.914.399 2.741A13.612 13.612 0 0 1 7.5 10.91V8.5H4.51zm3.99 0v2.409c.91.03 1.783.145 2.591.332.223-.827.364-1.754.4-2.741H8.5zm-3.282 3.696c.12.312.252.604.395.872.552 1.035 1.218 1.65 1.887 1.855V11.91c-.81.03-1.577.13-2.282.287zm.11 2.276a6.696 6.696 0 0 1-.598-.933 8.853 8.853 0 0 1-.481-1.079 8.38 8.38 0 0 0-1.198.49 7.01 7.01 0 0 0 2.276 1.522zm-1.383-2.964A13.36 13.36 0 0 1 3.508 8.5h-2.49a6.963 6.963 0 0 0 1.362 3.675c.47-.258.995-.482 1.565-.667zm6.728 2.964a7.009 7.009 0 0 0 2.275-1.521 8.376 8.376 0 0 0-1.197-.49 8.853 8.853 0 0 1-.481 1.078 6.688 6.688 0 0 1-.597.933zM8.5 11.909v3.014c.67-.204 1.335-.82 1.887-1.855.143-.268.276-.56.395-.872A12.63 12.63 0 0 0 8.5 11.91zm3.555-.401c.57.185 1.095.409 1.565.667A6.963 6.963 0 0 0 14.982 8.5h-2.49a13.36 13.36 0 0 1-.437 3.008zM14.982 7.5a6.963 6.963 0 0 0-1.362-3.675c-.47.258-.995.482-1.565.667.248.92.4 1.938.437 3.008h2.49zM11.27 2.461c.177.334.339.694.482 1.078a8.368 8.368 0 0 0 1.196-.49 7.01 7.01 0 0 0-2.275-1.52c.218.283.418.597.597.932zm-.488 1.343a7.765 7.765 0 0 0-.395-.872C9.835 1.897 9.17 1.282 8.5 1.077V4.09c.81-.03 1.577-.13 2.282-.287z" />
						</svg>
						&nbsp;Go to Promotion Website
					</a>
				</div>
			</div>
		</div>
	</div>
      
        <div class="footer">
		<div class="copyright">
			<p>Copyright © Designed &amp; Developed by <a href="https://axeldigital.asia/"
					target="_blank">AxelDigitalAsia</a> 2023</p>
		</div>
	</div>
       
</div>
</template>

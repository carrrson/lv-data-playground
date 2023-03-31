# LocalView Public Meetings Database
## Codebook

st_fips:
	Concatenated state + FIPS code identifying place of meeting.
state_name:
	Name of state.
place_name:
	Name of place as reported in U.S. Census.
place_govt:
	Identified government body.
place_{Pres|Gov|House|Sen}_dem2pv:
	2-party Democratic vote-share in last available {Pres|Gov|House|Sen} election.
place_{Pres|Gov|House|Sen}_dem2pv_last:
	2-party Democratic vote-share in last {Pres|Gov|House|Sen} election.
census_{2010|2015}_pop_est:
	Census population estimate in {2010|2015}.
acs_2018_pop:
	American Community Survey population estimate in 2018.
acs_2018_{white|black|hispanic}:
	American Community Survey estimates of the {white|black|hispanic} populations in 2018.
channel_id:
	URL ID for YouTube channel.
channel_title:
	Title of YouTube channel.
vid_id:
	URL ID for YouTube video.
vid_title:
	Title of YouTube video.
vid_desc:
	Description text for YouTube video (at time of scraping).
vid_length_min:
	Length of YouTube video (minutes).
vid_upload_date:
	Date of upload to YouTube.
vid_livestreamed:
	Whether or not video was live-streamed on YouTube.
vid_views:
	Number of views for YouTube video (at time of scraping).
vid_likes:
	Number of likes for YouTube video (at time of scraping).
vid_dislikes:
	Number of dislikes for YouTube video (at time of scraping).
vid_comments:
	Number of comments for YouTube video (at time of scraping).
vid_favorites:
	Number of times YouTube video has been favorited (at time of scraping).
meeting_date:
	Date that meeting took place. 
caption_text:
	Caption text, if available, with annotations.
caption_text_clean:
	Caption text, if available, without annotations.
channel_type:
	Who hosts the YouTube channel (when discernible).


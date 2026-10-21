# social-images

Public image hosting for the Law Offices of Darrin T. Mish Instagram carousels.

- `c/<carousel-id>/slide-1.jpg ... slide-7.jpg`: 120 carousels, 7 slides each (1080x1350 JPEG)
- `schedule.json`: posting order, date (9:00 AM America/New_York, Mon/Wed/Fri; #1 posted 2026-10-21, #2 on 2026-10-26), caption and image URLs for each post

Posts are published to Instagram through Windsor.ai by a scheduled task. Instagram fetches the images from the public raw URLs in `schedule.json`, so don't rename or move files until the schedule has finished (last post 2027-08-02).

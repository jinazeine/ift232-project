# ift232-project

CREATE TABLE `tbl_courses` (
  `course_id` int(11) NOT NULL AUTO_INCREMENT,
  `course_code` varchar(6) NOT NULL,
  `course_name` varchar(30) NOT NULL,
  `course_description` varchar(250) DEFAULT NULL,
  `course_type` varchar(8) NOT NULL,
  `course_nb_credits` int(11) NOT NULL,
  `course_lab` varchar(3) NOT NULL,
  PRIMARY KEY (`course_id`)
) ENGINE=InnoDB AUTO_INCREMENT=2 DEFAULT CHARSET=utf8;

<?php

#==>> Config

const CONTENT_GENERATOR = 'GEMINI';#  GEMINI, OPENAI OR BING
const CONTENT_LANGUAGE 	= "indonesian";

const EXTRA_POSITION 	= 2;# 0 = OFF, >1 ON
const EXTRA_CONTENT_MIN = 7;
const EXTRA_CONTENT_MAX = 10;

const LOOPING_TIMEOUT	= 100;# second
const TREAD_DELAY		= 0;# Seconds, 0 = OFF, ( auto max = value + 5 )
const GENERATE_COOLDOWN	= 5;# Seconds
const MAX_TRIES 		= 5;# Rotating Generator
const MIN_SUCCESS_RATE	= 99;# Minimal Success Rate dalam persen

const APIKEY_DElETE_ON_ERROR = TRUE;# TRUE or FALSE

const BADWORD_FILTER 	= FALSE;
const TITLE_BY_AI 		= TRUE;# TRUE or FALSE

const HEADER_IMAGES 	= FALSE;# TRUE or FALSE

#==>> Image Config
const IMAGE_GENERATOR 	= FALSE;# TRUE or FALSE
const MAX_IMAGE 		= 10;# 10 - 30
#======

#==>> Video Config
const YOUTUBE_VIDEO 	= TRUE;# TRUE or FALSE
const YOUTUBE_REGION 	= "ID";# ID or US
#======

#==>> BING Config
const MAX_ARTICLE_LEVEL = 30;# 10 - 30
#======

#==>> Ai Config
const AI_PROMPT_FOLDER 	= "article max";# \writable\prompt\folder name
const WRITING_TONE 		= "professional";
const WRITING_STYLE 	= "informative";
const CONTENT_TYPE 		= "informatical article";

#==>> OpenAi Config
const OPENAI_API_MODEL 	= "gpt-3.5-turbo";

/*
    GPT 3.5 MODEL LIST:
    gpt-3.5-turbo
    gpt-3.5-turbo-0301
    gpt-3.5-turbo-0613
    gpt-3.5-turbo-1106
    gpt-3.5-turbo-16k
    gpt-3.5-turbo-16k-0613
*/
#======

#==>> AUTOPOST CONFIG

const AUTO_POST	 		= FALSE;# TRUE or FALSE
const WP_URL			= 'http://hinet.co.id';
const WP_AUTHOR_USERNAME= 'Zulfahmi';
const WP_AUTHOR_EMAIL	= "akbarsilohon@gmail.com";
const WP_APP_PASSWORD	= 'RlTYRAQSwitnTw6kD83oBxUb';

#======




#==>> EXPORT CONFIG

const MINIFY_HTML	 	= FALSE;
const FIX_ILEGAL_WORD	= TRUE;
const SLUG_ENCODE		= TRUE;

const WP_DRAFT 			= FALSE;# TRUE or FALSE

const PUBLISH_PER_XML	= FALSE;# TRUE or FALSE
const START_DAY 		= "-1 day";# day, days, month
const ARTICLE_PER_DAY 	= 3;
const XML_PER_NICHE 	= 0;
const ARTICLE_PER_XML 	= 50;

const HOME_FEED_LIMIT	= 10;
const SITE_BRAND 		= "Imake V2";
const POST_EXTENSION 	= ".html";


const CSV_DELIMITER 	= ',';
const CSV_QUERY 		= 'niche, keyword, slug, image, title, tag, desc, content, publish';

#======

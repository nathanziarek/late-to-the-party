{{{
    "summary": "",
    "keywords": [],
    "publishedOn": "September 28 2011"
}}}


# Speeding up the web with Amazon Silk

Amazon today released the details about a few upcoming Kindles. The devices themselves are interesting, although evolutionary. The [Kindle Fire][1] might be the first Android tablet to seriously challenge the iPad in the tablet space.

The fascinating bit is the new browser Amazon has developed named [Silk][2]. It utilizes Amazon's massive cloud computing infrastructure to offload some of the work of rendering a page. It may turn out to be nothing more than the system Opera has in place for the Opera mini browser, but it's an interesting rethinking of the browser at a time when highly-portable devices are tearing up the sale charts (netbooks, smartphones, the iPad).

Silk works by funneling parts of your request through AWS. Amazon claims the browser is able to make real-time, dynamic decisions as to how to use the cloud infrastructure. Are you requesting a 10 megapixel image? EC2 can rapidly downsample and deliver an 80kb instead of an 80Mb one. Amazon doesn't mention it, but they are also very capable of compressing the HTML, both in terms of removing whitespace and gzipping. Add together a number of the
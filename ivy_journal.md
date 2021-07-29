# Ivy's Summer PRIME Program Journal

## Tuesday, July 6

Our first day started off slowly, with difficulties connecting to CoworkCafe's
WiFi. Although WiFi difficulties took up a large chunk of the day, I was able
to complete a vim tutorial and a
[Unix tutorial](http://www.ee.surrey.ac.uk/Teaching/Unix/index.html). I also
began reading up on
[Git](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).


## Thursday, July 8

The second day of the internship had a much smoother start. There were no
difficulties connecting to WiFi or getting online. We began today with learning
Git. Our first step was the SSH key. We learned the background of it, why it's
better than a password, and how to generate and upload it to GitHub. Next, we
cloned the repository and created Markdown journals. We applied what we learned
about Vim on Tuesday to edit these journals. Next, we learned how to add,
commit, push and pull to make sure that our work is saved and uploaded into the
repo. I learned about merges, and how merge conflicts can occur. Finally, we
applied this to push our journals and pull our colleagues' journals. Towards the
afternoon, we met Colombene. She introduced us to UX, or User Experience. I 
think my main takeaway from that was there are a lot of different factors to 
juggle when looking at software or products from a UX point of view. We finished
off the day by making a plan to install Decidim on Friday.

## Friday, July 9

We began today by having a morning meeting discussing our reasons for doing 
PRIME and what we hope to gain from this experience. Then, we reviewed our goals
for the day, which included installing Decidim. After discussion with Jeff and
then amongst us interns, we decided to follow the helpful instructions sent by 
Louis. There were some roadblocks along the way, but we were able to resolve 
them. For example, installing Ruby and some of the other software required a git
clone. However, we received an error message that 'git' wasn't recognized by the
program. We problem solved this by looking up how to install git, and then 
executing that command. After resolving this and continuing forth, we ran into a
problem installing Passenger to connect Ruby with Nginx. Specifically, we got an
error of unmet dependencies. We found some tips online, but they didn't resolve
the problem. We contacted Louis for some help with it. It turns out, we needed
to use Ubuntu instead of Debian. So, we went through the lengthy process of
turning our home directories to tar and then putting it onto a new Ubuntu 
server. While this was running, we investigated more into Decidim. From the 
Decidim Docs, I learned the following information:
 Participatory Spaces | Participatory Components
-------------------------- | -----------------------------
channels to participate through | mechanisms to enable interaction
processes, initiatives, consultations, and assemblies | meetings, pages, proposals, and surveys

## Monday, July 12

Today, we began our exploration of Decidim. In the end, we were unable to get 
it up and running on our own, so NOVA Web did it for us. We all created our own
processes in Decidim and explored the different components within the processes.
So far, most of the components are fairly straightforward, with the exception of
the Proposals. That is quite confusing. Right now, my hypothesis is that in 
order to have working proposals, you have to upload a participatory text. I
uploaded the Resources Link file, which is on GitHub, just to test it out, but
I have to figure out how to delete proposals. I have accepted and rejected some
proposals, but it doesn't seem to remove them from the list of proposals. My 
goal for tomorrow is to figure out how to delete proposals, maybe by making them
into "past processes" or along those lines. I created a meeting for tomorrow, 
changed the color scheme of the website, created a process group, among other 
features but there are still more to explore. 

## Tuesday, July 13

This morning, Hisham let me know that proposals can't be deleted by design, 
does make sense to me thinking about it from a participatory democracy 
perspective. However, I was able to unpublish the "Proposals" page I had
created, so it's no longer viewable to the public. I created another Proposal
component, but named it "Your Ideas." This time, I changed up the settings in
the configurations to disable Participatory Texts. Therefore, when I created a 
proposal, I didn't need to also upload a Text and I could just do simple 
Proposal. It's lot easier without doing the text, which looks really strange
on the page since it has to have headings and subheadings on top of the proposalitself. But the website makes the subheadings and proposals look really similar,
even making it so the subheadings can be supported, endorsed, etc, like a real
proposal. 
Moving on, today I explored the *Accountability* component of Decidim. I thought
this would be a lot easier than it was, but there are a lot of things that go
into it. It's basically a progress report on projects and other stuff. So far, I
am pretty sure that you have to have categories set up in order to actually 
display anything on the Accountability tab. So, on your process' dashboard, look
below "Components" and it's sub-features to "Categories" and create some stuff
there. Use the "Parents" feature to create sub-categories. Once this is done,
you can use Accountability, which personally, I think needs a better name. Next,
keeping in mind the project you are reporting progress on, create status' that 
can apply to that project. Finally, press the new results button to create a
progress chart. You can link it to a Project from Budgets or a Proposal. Make
sure that you link it to a category so that it shows up in the Accountability 
tab. You can also put progress reports inside of other ones, for example if you
have a large project consisting of several smaller ones, you can put the smaller
ones' progress reports inside of the other ones. As time goes on, and you want 
to update the progress or scope of the project you can. There is a version 
history on the public site, which shows the updates made to the project. You can
also add to the "Project Evolution" in case the project expands or contracts. 
The project evolution is displayed on the website as well, in a much more 
readable fashion than the version history. 

# Thursday, July 15

Today, I worked on some more features of Decidim. I played with the *Debates* 
component, which I think really should have been named discussion. This is 
fairly similar to Proposals except that you can't like or dislike it, and it 
can't be officially accepted or rejected as proposals can. This morning, Jeff 
briefed us on his vision for the application of Decidim with regards to US Tech
Workers Coop. This involved having different groups on the site so that everyone
can see everything but only certain people can interact with it. We played 
trying to find a solution: I made a group, but that doesn't really do anything 
except allowing you to make a conversation with them. Max made a scope, but that
didn't work very well either. I looked through the Meta Decidim *I Have A
Question* page, and found a [post](https://meta.decidim.org/processes/supportforum/f/705/proposals/15835?locale=ca%2Ff%2F705%2Fproposals%2Fnew&order=recent&per_page=100) which had the instructions to do what we wanted. Assemblies can be
used to really configure who is able to see and participate in things. There are
several different settings in assemblies:
Type of Assembly | Who Can See | Who Can Participate
---------------- | ----------- | -------------------
Default | Everyone | Everyone
Transparent | Everyone | Specific Users
Private | Specific Users | Specific Users

We are interested in the Transparent assembly, where only members of NOVA Web 
can vote and participate, but everyone can see what's going on. Besides the
permissions, an assembly is essentially the same as a process. You can add all
the same components, categories, info, and you can create admins. Another cool
thing is that you can create child assemblies. This is super useful and fits in 
wonderfully with Jeff's vision of using it in the USTWC site. Each Coop can have
it's own Assembly page. Within that, if they want to vote on stuff within their
coop, then they can create an assembly inside of it to do that. Also, for NOVA 
Web, this is useful for when there are non-voting members of the coop that still
want to participate. They won't be members of the specific voting issue, but 
they can still see what's going on. Another useful thing could be setting up a 
voting assembly for the USTWC as a whole. Each coop could have a representative
in that assembly, and USTWC could vote on issues that affect the whole
organization. 
Later that afternon, we talked with Louis and discussed some goals for the next two weeks of PRIME. We decided that continuing to explore Decidim is not a good plan as we are just about done with that. We were talking about how setting up
Decidim was a real challenge in a way because there was confusion over what 
things actually did and some things can't be deleted. So, if you're figuring out
how things work, you really have to do it on a dogfood website or else you'll 
have a bunch of junk on the actual site. Louis brought up the fact that really, this could be solved by us. We could write documentation for Decidim, which 
would really help people to use it. It's so much easier to do something when 
someone tells you *what* and *how* to do it, without necessarily knowing the 
*why* of it. That's one option for the rest of the internship, and another 
option would be to play around more with the back-end stuff of Decidim. For 
example, one thing that I found was changing the currency. Decidim doesn't allow
that in admin dashboard, you have to go in to the app config file. Another thing
that I'd like to do in there is go into the database and manually remove the 
proposals component that I created, which is obsolete. However, if we're playing
around with the back-end side of things, that is at risk of breaking the site.
So, Louis suggested getting a second instance of Decidim up and running on the
same server: one for front-end exploration and the other for back-end. If the
secondary one crashes, it's not too big of a deal because we can just continue
using the primary in the meantime. As well, apparently installing Decidim for 
the second time on the same server is a lot easier because a lot of the stuff is
already there. It would be a good way for us to expand our knowledge, which is
why we have plans to do so on Monday. 

## Friday, July 16

This morning, we used our daily meeting to debrief Jeff on the outcome of our 
discussion with Louis (see above). Afterwards, we tested out computer
functionality for our upcoming meetings with OpenSource Politics and FundAction.
Next, we prepared for our meeting with FundAction by coming up with a list of
questions to ask. We messed around with Assemblies a bit, creating a Test Child
Assembly for the PRIME Assembly. 

## Monday, July 19

We met with FundAction at 11:15, so we spent that morning preparing by testing
out the computer and going over and adding some more questions. The FundAction
meeting was somewhat helpful for seeing what actual Decidim users felt like. She
said that they pay someone to set up Decidim for them, and that it was 
definitely a paid job. She also said that many of her colleagues didn't really
like using it since it's somewhat complicated. She did mention that they don't 
provide any intro or training for it, but people rely on the members who invited
them to join. I think that this kind reassures us that yes, people will pay for
Decidim installation and that Documentation is super useful and is desperately
needed by Decidim. It wasn't super helpful for learning about deployment and 
other technical features of Decidim, but it did provide a new perspective on it.
Afterwards, we met with Louis to talk about how we were having trouble with 
assemblies. We couldn't create proposals on US Tech Worker Coops on the assembly
even though we were members and the one on Dogfood worked. Louis said he would 
look into it more.

## Tuesday, July 20

Today, we met with Open Source Politics. The representative was super helpful, 
she walked us through their business plan and even offered to help NOVA Web on
their journey by partnering and giving a tutorial. I think we were all pretty
pleased about that meeting, but it definitely was a lot to absorb. Now that we
have some positive news about Decidim, we re-evaluated our PRIME goals for the 
summer. In a way, we had two options: continue with the more technical side, by
developing documentation, or switch to the more social/political side, by 
researching OSP and market interest in participatory democracy or budgeting. We 
also figured out the problem with assemblies. It was that you have to also add 
people as "Private Users", not just members. I did this for Dogfood's PRIME 
assembly but I completely forgot that I did that until Louis and Max figured it 
out. 

## Thursday, July 22

Today, we decided that we were going to go ahead with information gathering
about Decidim. I uploaded a [file](https://github.com/jelkner/decidim2021summer-sprint/blob/main/OSP_info/reasoning.md) to Git with some of OSP's reasoning for
why they exist and why participatory democracy with open source software is so
important. I got my information from a very interesting article by one of the 
founders of Open Source Politics. 

## Friday, July 23

Today, during our meeting with Jeff we got a little more information about our 
objectives for our investigation into OSP and Decidim as a business plan. I 
spent the morning researching foundations that suppot grants for civic 
participation, which I created a [file in GitHub](https://github.com/jelkner/decidim2021summer-sprint/blob/main/civic_participation_grants.md) for. One 
foundation seemed particularly interesting, called the [Foundation to Promote 
Open Society](https://www.opensocietyfoundations.org/), which is supported by 
George Soros. 

## Monday, July 26

Today, I continued to look for new reasoning to support why participatory 
democracy is good and works well. I came across an [article](https://ssir.org/articles/entry/the_moment_for_participatory_democracy) in the [Stanford Social
Innovation Review](ssir.org) by [Hollie Russon Gilman](https://www.hrgilman.com/), the former open government and innovation policy advisor in the Obama White
House. The article lays out three models that can overcome the challenges to 
mobilize civic life and participation: 1. giving government data to citizens, 2.
giving a direct connection between citizens and their representatives, and 3. 
giving citizens a part in policy. I think that Decidim pretty easily fulfills 
all of these aspects. Using the blog feature, governments can post updates on 
government functionality, they can use the accountability feature to post 
progress reports on projects, and they can send out newsletters to directly 
target specific segments of the population. The surveys feature allows for 
citizens to let the government know what they want and the meetings feature 
facilitates the creation of face-to-face interactions between politicians and 
citizens. Finally, the proposals feature and the budget feature allows citizens
to write their own ideas for government spending/legislation and vote on which
proposals or projects they'd like to do. 
Later, we called Louis to solidify our plans for the last few days of PRIME. 
It's gone by so quickly, so it does feel weird that there are only a few days
left. We decided that we could choose one of the foundations and look into the 
grant requirements and what information would be needed to write a grant so that
Louis and NWD will be able to write the grants quicker. Obviously, we aren't 
going to write a grant...that would take a lot of time and isn't necessarily
even helpful since we might do it in a way that NWD doesn't really want. 

## Tuesday, July 27

Today, I worked on gathering some more information about the grants and 
foundations. Most of them aren't accepting any more grants this year, which
makes sense as the financial year is about to close. Some of them don't accept 
solicitations for grants. Others have you submit a letter of inquiry, and the
foundation will get in touch if they are interested or not. I think that that
type makes the most sense because it builds trust, as Jeff said. It also means
that the risk of getting rejected after you spent all that time researching and
writing a grant proposal is a lot lower because you are more likely to just be 
rejected after the initial letter round. We also began a process on Decidim to
decide where to go for lunch. Finally, near the end of the day I tried to 
reorganize the list of grants. I wanted to highlight the ones that have the 
letter of inquiry application process, because those are the ones that Jeff was
interested in targeting. However, I couldn't figure out how to highlight text on
Git. So, instead, I decided to start reorganizing the list. I realized that the
way I had done the list wasn't very smart. I kept it in the same order as on the
list that I found, which isn't very smart because it makes the list that I made
pointless since it was basically the same one as the online list. So, I decided
to find a new way to organize it, in a way that specifically pertained to NWD. I
decided to go with organizing it by application method and began doing that.

## Thursday, July 29

I started out by finishing the reorg of the grants list. I ordered it by mathod of application, with differnt types as follows: Letter of Inquiry, Deadline TBA,
Deadline Passed, and Not Accepting Solicitations. Then, I started looking into 
how to certify the union. I'm not entirely sure about what step in the process
the AEA is in, but I think they probably still need to be certified. So, they 
need to choose one person to be their representative, and get signatures to 
demonstrate that the person has at least 30% of the employees' support. Then,
the AEA needs to file the document linked in this file.

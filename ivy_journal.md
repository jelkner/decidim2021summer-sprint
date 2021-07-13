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

Business Bingo
==============

`Feature Squad <Feature%20Squad>`__\ s use a simple collaborative
estimation method called {{Planning Poker}} to determine the relative
effort needed to deliver different stories. These {{Story Point}}
estimates can be converted into dollars and time by combination with
delivery throughput measurements called {{Velocity}}. But they’re not a
suitable input to release planning because:

-  They don’t and were never intended to estimate a `Feature
   Budget <Feature%20Budget>`__. To get at a budget estimate you’d have
   to multiply them by the `Story Velocity <Story%20Velocity>`__, which
   inevitably and intentionally varies from team to team and, within a
   single team, from time to time.
-  You can’t produce story point estimates without breaking down
   `Feature <Feature>`__\ s into `Stories <Story>`__. If you wait until
   you’ve done that for all your features, you’ve stepped out of
   Agile-land back into Waterfall-land to have an Analysis
   `phase <phase>`__. But if you don’t commit to some kind of
   Feature-level release plan you’ll wind up with the Business rebelling
   because of a lack of `predictability <predictability>`__, which will
   also take you back to Waterfall-land.
-  There are plenty of costs associated with delivering a Feature that
   aren’t captured by Story estimates, especially to do with `Feature
   Integration Testing <Feature%20Integration%20Testing>`__, `System
   Integration Testing <System%20Integration%20Testing>`__,
   `Marketing <Marketing>`__ and `Opex <Opex>`__. These must be taken
   into account when budgeting Features for a release plan.

**Therefore,**

Business Bingo is a simple way to quickly determine the budget (time \*
resource) and relative ROI (Royal Cod) of a feature set without waiting
for its features to be broken down into estimable stories. It bases
estimates and priorities on the historical costs of a set of features
delivered in previous releases and takes costs of analysis and operation
into account too. It also provides a simple method to “monetize” `Story
Points <Story%20Points>`__ in terms of feature budgets in `Feature
Points <Feature%20Points>`__.

Best of all, **Business Bingo** is easy, fun to play, and quickly aligns
business and technical stakeholders. It works like this:

1. Write Fibonacci numbers from 1 to 89 on cards and lay them out in a
   row across a large table. There’s nothing magical about Fibonacci
   numbers - we use them because they consistently lead people to argue
   in terms of trade-offs - is feature A really as big as feature B +
   feature C, and so on.

2. Select three previously delivered and deployed features with well
   documented costs, one small, one medium and one large. Call these
   probes. Describe each probe in story-normal form commensurable with
   the roadmap features you want to estimate and represent their
   complete delivery costs - including documentation, hotfix, opex, the
   whole nine yards - in terms of `Feature
   Point <Feature%20Point>`__\ s. Place the three probes under the
   Fibonacci numbers that match their respective magnitudes in feature
   points.

3. Pick a feature from your `Acceptance Matrix <Acceptance%20Matrix>`__.
   Compare it with the probes, starting with the middle one, to evaluate
   its relative size in Fibonacci multiples of feature points.

4. As you add features, sort them into the appropriate Fibonacci column.
   Continue to compare features this way until there are none left to
   compare. If the estimators cannot agree on the Fibonacci number for a
   feature, split it into pieces they can estimate separately.

5. Take features that wind up in the last 3 columns and break them into
   pieces you can estimate separately. This granularity limit greatly
   improves the overall quality of the estimates.

6. To estimate relative business value, you simply pick a different set
   of 3 probes - one for an existing deployed feature that the PO says
   has low business value, and then one that’s critically important to
   business function, and then one roughly in between. Place them at 3,
   13 and 55, respectively, and the rest of the Bingo game runs as
   above.

7. All `Product Squad <Product%20Squad>`__ members collaborate in a 3rd
   pass to calculate `Risk <Risk>`__\ s.

8. Record all three numbers on each feature card as input to `Royal
   Cod <Royal%20Cod>`__ prioritization.

There’s no dollar quantification of the return here, but we’ve found
business stakeholders quickly converge on which features are worth more
than which. And the conversations they have in getting to agreement are
extremely illuminating - the technical team members need to listen
carefully and ask questions to make certain they share the business
context.

`ToDo <ToDo>`__: update this description to account for return
estimation via {{Pirate Canvas}}.

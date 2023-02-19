.. code-block:: haskell

    instance User MC where
        type Dev MC = (FOSS, Neuroscience)

        loves = [Wayland, Python, Haskell]
        studying = [Haskell] >>= 🧠

        working =
            case now of
                Night -> Qtile
                Day -> Improbable

        links =
            Links
                { fediverse = "faaraah.xyz@gmail.com"
                , web = "farah.xyz"
                , repos = "farah-xyz/wayland-dots"
                }

.. image:: https://github-readme-stats.vercel.app/api?username=Farah-xyz&count_private=true&title_color=fff&icon_color=79ff97&text_color=fefefe&bg_color=0a0c10&hide_title=true
   :alt: Farah-xyz GitHub stats

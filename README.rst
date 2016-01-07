Tabview
=========

Forked from: [tabview](https://github.com/firecat53/tabview)

Added external keybinding function capability. Function must have one argument which will become a Viewer class istance once called.

Usage example:
    .. code:: python

        import tabview as t
        a = [["a","b","c"], ["d","e","f"]]

        def test_item_pos(a):
            print a.x, a.y
            
        t.view(data=a, key_update={'+', test_})
